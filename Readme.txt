Introduction

This is the readme file for Paytm Payment Gateway Plugin Integration for Zencart v1.5.x based e-Commerce Websites. 
The provided Plugin helps store merchants to redirect customers to the Paytm Payment Gateway when they choose PAYTM as their payment method. 
After the customer has finished the transaction they are redirected back to an appropriate page on the merchant site depending on the status of the transaction.

The aim of this document is to explain the procedure of installation and configuration of the Package on the merchant website.


Installation and Configuration

- Copy the files as per the directory structure in the module.

1) encdec_paytm, paytm_version.txt-: Put this file under "includes" directory.
2) paywithpaytm-: put this file under "includes/modules/payment" directory.
3) paywithpaytm(language file)-: put this file under "includes/languages/english/modules/payment"

- Log in to your Administrator Area.
- From the backend of your Zencart site (administration) select Modules -> Payment. 
- Click on "PaywithPaytm" Gateway and click on install button.
- After module Installation, configure it.
- You should select the Transaction mode, enter paytm Merchant id, Merchant key, website in the listed parameters on configuration tab.
- Then click on Update.

# Paytm PG URL Details
	staging	
		Transaction URL             => https://securegw-stage.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw-stage.paytm.in/merchant-status/getTxnStatus

	Production
		Transaction URL             => https://securegw.paytm.in/theia/processTransaction
		Transaction Status Url      => https://securegw.paytm.in/merchant-status/getTxnStatus
