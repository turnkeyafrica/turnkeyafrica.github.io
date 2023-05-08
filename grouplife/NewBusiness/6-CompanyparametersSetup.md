**TURNQUEST LIFE INSURANCE MANAGEMENT SYSTEM (LMS)**

**SYSTEM USER MANUAL**

Contents

[1 Quotation & New Business](#quotation--new-business)

[1.6 Company parameters](#company-parameters)

[1.6.1 Number formats](#number-formats)

[1.6.1.1 Sequence type](#sequence-type)

[1.6.1.2 Sequence Template](#sequence-template)

[1.6.1.3 Sequence Products](#sequence-products)

[1.6.2 Debit and Credit Note Narratives](#debit-and-credit-note-narratives)

[1.7 Accounts Mapping](#accounts-mapping)

[1.7.1 Transaction Types](#transaction-types)

[1.7.2 Product Transaction Accounts](#product-transaction-accounts)

[1.7.3 Premium Receipting Accounts](#premium-receipting-accounts)

[1.7.4 Reinsurance surplus treaty](#reinsurance-surplus-treaty)

# Quotation & New Business

This is the process by which insurers assess the risks to insure and decide on premium to charge for accepting those risks. The TurnQuest application takes care of new business in three sections.

## Setup Prerequisites

## Company parameters

### Number formats

This screen is used to set the numbering formats for different areas in the application i.e. Quotation, Policy and Claims numbering.

#### Sequence type

Select **Number Format** link from the **Company Parameters** sub module of the **Setups** module, the screen below is opened.

![](media/424924781e9bd1078bd1f1d8c72ceaaf.png)

Highlight the class of business, then click on the ![](media/4f2eee20658e219214ebfe209660d87f.png) button under Sequences to define a sequence type.

![](media/035ede8a186d23adcd0577e22597df24.png)

-   Short description of the sequence
-   Description of the sequence
-   Sequence Type- Policy, Quotation, Claims or Agent number
-   Length of sequence
-   Separator: - Symbol that separates the different parameters i.e. -, /, \# etc
-   WEF: - date from
-   WET: - date to if the sequence has a definite end date, else leave this field blank

Click on the save button to save the record

#### Sequence Template

After creating the sequence type above, highlight the record and click on the![](media/463292879c3e4ed0c850ad207df1d923.png) button at the **Sequence Templates** to create the sequence template.

![](media/4254379b0dccd81932a83cadfb3c51bb.png)

Provide the sequential order of the number components including the separator. For every component click on save to update the record before moving on to the next one.

#### Sequence Products

The templates once defined are attached to the applicable products.

Highlight the sequence, the click on the ![](media/463292879c3e4ed0c850ad207df1d923.png) button at the products section

![](media/5fe08c5dd029cd3e47d94ce103bd9c76.png)

Select the product and click on save. Repeat the selection for all the applicable products.

### Debit and Credit Note Narratives

This is used to define debit and credit note narrative to appear when these reports are run at varying points of the application.

Select **Narratives** from the **company parameters** sub module of the **Setup** module, the screen below appears

![](media/44ca388dd53f52ff773cb0c407a63730.png)

Highlight the transaction type and click on the ![](media/698fed03b08b2850c3191fabfb6f1c0c.png) at the Narratives section to define the debit or Credit Note narrative

## Accounts Mapping

This module is used to do the mapping for the accounts updated in the financial system when a transaction is authorized in the Group Business system.

### Transaction Types

1.  To view the screen, click in the **Setup** module select the **Accounts Setups** menu item then select the **Transaction Types** submenu, the screen below appears

![](media/395a115c72e21b051807727dcd8fa132.png)

1.  All transaction types are predefined; the user only needs to update the relevant Accounts code to be updated in the Finance application
2.  To define a new transaction type, click on the New button, the screen below is opened

![](media/3ee62c408f906d4af397439a7b1b6606.png)

1.  Select the **GL code** and **contra GL code** (for those that apply) for transactions that are not product applicable (product specific is defined elsewhere)
2.  Select **Type** which is predefined in the application, the system will automatically update the **code**.
3.  The **Description** is provided by the financial/accounting department to identify with the various names given to the items affecting the accounting system.
4.  **Application level**: -Specify whether product applicable or not

### Product Transaction Accounts

If product applicable select the **Accounts** menu item from **Core Setup module** then select the **Product** **Transaction Accounts** submenu, the screen below appears

![](media/e7ddaf69df892f4baa54b52b8dcc3ad7.png)

Use **populate revenue items** button to attach all accounts transactions that are defined as product specific.

To create new account per product, click on the New Button

![](media/b9dc9b395ef890f7ce80de3bc76049c2.png)

Select the applicable transaction type, Account no and the control account no if it applies

### Premium Receipting Accounts

The accounts for the transactions below need to be set up before receipting can take place.

NB: - The prerequisite is these accounts should exist in the financial system

1.  DIRECT RECEIPT code type is DR_RCTGB
2.  UNDERWRITING (POLICY) PREMIUM code type is UP_GB
3.  COINSURANCE MEDICAL FEE code type is COIN_MED
4.  COINSURANCE SERVICE CHARGE code type is COIN_SCS
5.  COINSURANCE PREMIUM COMMISSION code type is COIN_COM
6.  COINSURANCE PREMIUM TAX code type is COIN_TAX

### Reinsurance surplus treaty

1.  FIRST SURPLUS REINSURANCE code type is FSTSUP (Select Reinsurance Premium and overwrite the code RP)
2.  FIRST SURPLUS COMMISSION code type is FSTCOMM (Select R/I Commission and overwrite the code RC)
3.  SURPLUS PREMIUM RETAINED code type is FSTPREM (Select RI Retained Premium and overwrite the code RPR)
4.  SURPLUS STAMP DUTY code type is FSTDUTY (Select RI Stamp Duty and overwrite the code RSD)
5.  R/I REINS PREMIUM TAX code type is RPTAX
