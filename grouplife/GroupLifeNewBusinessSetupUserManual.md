**TURNQUEST LIFE INSURANCE MANAGEMENT SYSTEM (LMS)**

**SYSTEM USER MANUAL**

**QUOTATION & NEW BUSINESS SETUPS**

**TURNKEY AFRICA LTD**

| **Version** | **Date**   | **Remarks**           | **Done By** |
|-------------|------------|-----------------------|-------------|
| 0.0         | 21/12/2010 | Initial Training Plan | Lillian     |
| 1.0         | 18/08/2015 | Updated               | Justin      |
| 2.0         | 26/04/2016 | Updated               | Armstrong   |
| 3.0         | 13/11/2017 | Updated               | Jeremy      |
|             |            |                       |             |

Contents

[1 Quotation & New Business](#quotation--new-business)

[1.1 Setup Prerequisites](#_Toc132639430)

[1.1.1 Organization Data](#organization-data)

[1.1.1.1 Organizations](#organizations)

[1.1.1.2 Region](#region)

[1.1.1.3 Branches](#branches)

[1.1.2 Accounts Data](#accounts-data)

[1.1.2.1 Accounts Type](#accounts-type)

[1.1.2.2 Accounts](#accounts)

[1.1.2.2.1 Defining](#defining)

[1.1.3 Clients Data](#clients-data)

[1.1.4 Service Providers Data](#service-providers-data)

[1.1.4.1 Service Provider Types](#service-provider-types)

[1.1.4.2 Service providers](#service-providers)

[1.1.5 Banks](#banks)

[1.1.6 Occupations Data](#occupations-data)

[1.1.6.1 Life Classes](#life-classes)

[1.1.6.2 Occupations](#occupations)

[1.2 Classes and Products Definition](#classes-and-products-definition)

[1.2.1 Product Setup](#product-setup)

[1.2.2 Relation & dependents Type](#relation--dependents-type)

[1.2.3 Cover types definition](#cover-types-definition)

[1.2.4 Product Cover types](#product-cover-types)

[1.2.5 Product Cover Types Dependants](#product-cover-types-dependants)

[1.3 Rates Setup](#rates-setup)

[1.3.1 Premium Structures (Premium Masks)](#premium-structures-premium-masks)

[1.3.2 Premium Rates Loading](#premium-rates-loading)

[1.3.3 Premium Rates](#premium-rates)

[1.3.4 Free Cover Limit Tables](#free-cover-limit-tables)

[1.3.5 Interest rates](#interest-rates)

[1.3.6 Discount types](#discount-types)

[1.3.7 Loading types](#loading-types)

[1.3.8 Claim experience](#claim-experience)

[1.3.9 Short term rates](#short-term-rates)

[1.3.10 Profit share factor](#profit-share-factor)

[1.3.11 Tax types](#tax-types)

[1.3.12 Tax rate by product tax type](#tax-rate-by-product-tax-type)

[1.3.13 Life Premium Commission Rates Definition](#life-premium-commission-rates-definition)

[1.4 Medicals Setups](#_Toc132639467)

[1.4.1 Medical Tests](#medical-tests)

[1.4.2 Facilitator Specific Test Rates](#facilitator-specific-test-rates)

[1.4.3 Medical Groups](#medical-groups)

[1.4.4 Medical requirements](#medical-requirements)

[1.4.5 Provisions](#provisions)

[1.4.5.1 Product Provision](#product-provision)

[1.5 Reinsurance Setup](#reinsurance-setup)

[1.5.1 Treaty Types & Treaties](#treaty-types--treaties)

[1.5.2 Treaty Setup](#treaty-setup)

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

### Organization Data

To be defined in the CRM application

#### Organizations

Strictly loaded prior to usage of the system to maintain data integrity.

#### Region

1.  Select the organization
2.  Click on the region tab.

![](media/589e44885ae1498ef8703877a3ba84b1.png)

1.  To define new region, click on the new tab

![](media/97ee858c1214a2da46c02b9e7dab727f.png)

1.  Enter details and save

#### Branches

Click on a region under which to define the branch

Click on the branch tab

Click on the new button to define the branch

![](media/ca2a7c3984eb84cf3f76957803d75533.png)

### Accounts Data

To be defined in the CRM applications

Used to define account types and accounts i.e. In-house Agents, Agencies, Brokers, Coinsurance Co, Reinsurance Co, Marketers

#### Accounts Type

Strictly loaded prior to usage of the system to maintain data integrity.

#### Accounts

Used to define the different accounts used during transactions

##### Defining

1.  Click on the accounts menu

![](media/37cb3b91d6fcfd5cdd7dd8b4f836b1f9.png)

1.  Select the account type, click on new to define a new account

![](media/17e7692ba710607a1415299229785b03.png)

1.  Assign to system once account is saved

![](media/414422e7589b5c0dbb1969f79efb6d16.png)

### Clients Data

To be defined in the CRM applications but the system provides a setup shortcut at the transaction point

Used to define clients

1.  Click on the clients’ menu
2.  Click on create/update client tab, select the client type i.e. corporate for group schemes, enter new client details

![](media/b94dcf5d641b01960222d8896b69889d.png)

1.  Assign client to the life system

![](media/cc8e1837faeec6266de93a56b9a37cf7.png)

### Service Providers Data

To be defined in the CRM applications

Used to define service provider types and service providers

#### Service Provider Types

Strictly loaded prior to usage of the system to maintain data integrity.

#### Service providers

Used to define Doctors, Hospitals, clinics, doctor etc

1.  Click on service provider menu
2.  Select the service provider type, click on new and define service provider

![](media/66a50e68f4f3f02288a7c8d52da7112d.png)

1.  Assign the service provider to system

![](media/b0caaa1a9964cf61fcf6b20348a619fc.png)

### Banks

Banks are necessary for clients who use Direct Debits, Electronic fund Transfer and bankers order. This data should be provided by finance and can be done through data loading (Data Loading)

### Occupations Data

To be defined in the LMS applications

#### Life Classes

Strictly loaded prior to usage of the system to maintain data integrity.

#### Occupations

1.  Click on setup module
2.  Click the **Group life occupations** sub menu, from the **U/W and Quotation Setup** menu
3.  Click on a class at the **life class occupation block** and click on ![](media/6da9d44846d550220b57a41ee374285c.png) to define a new occupation

![](media/a53ce52d893898ba403e16b9a1ac4044.png)

## Classes and Products Definition

This screen is used to define the classes and products in the life insurance department i.e. Group Life is a product under the Group class of insurance.

Product setup to be illustrated is Group Earnings with investment rider.

### Product Setup

Select **products and classes definition** from the **U/W and quotations setup** menu item of the **Setup Module**

The screen below appears

![](media/c9fa41551bfce60069624c6d0721a905.png)

1.  In the **product definition** tab enter the details associated with the product
    1.  **Product ID**: - Code for the product
    2.  **Description**: -Product Full name
    3.  **Product Type**: - Select Earnings Product.
    4.  **Umbrella product**? – Select No from the drop-down menu.
    5.  **Override Max Entry Age** – Select Yes if you accept members whose age is above the Max age limit set below.
    6.  **Minimum & maximum age limit (years)**: - Age limits for the product.
    7.  **Reinsurance Max Entry Age**: - Maximum age for members accepted by the reinsurer. Leave It blank for group earnings.
    8.  **Minimum & maximum Term** of policy: -Allowed term range for cover
    9.  **Policy Prefix Code**, **Proposal prefix** and **Claim Prefix code**: - short description used in the automated policy, proposal or claim number generation
    10. **Cancellation Notice (days): -** Number of days allowed for a client to notify the insurer before cancelling his or her policy
    11. **Open cover:** – Since earnings is an annual cover select no.
    12. **Default date of birth**: - The date of birth adopted in the event that a client provides only the year of birth.
    13. **Rein Max Period (days)**: - This is the grace period allowed for reinstatement after a policy lapses.
    14. **Is it a loan product**: - Specify whether Sum assured is based on issued loans? Since its not applicable for Earnings products selected No.
    15. **XOL Allowed**: -Select Yes if Excess of loss is allowed at claims processing
    16. **Weekly Indemnity limit**: - Define weekly indemnity payment maximum allowed number of weeks
    17. **Refund Commission**: - Select Yes if refund of commission is allowed on refund of premium transactions.
    18. **Refund allowed**: - Whether refund is allowed on early exit of members
    19. **Initial schedule endorsement allowed**: - used for capturing initial schedule where Aggregate details were used.
    20. **Product covers**: - Specify whether product covers only self, self & dependents, self & joint members or both.
    21. **Partial Cancellation allowed**: - for policies that cover O/S loans to extinction. Select No since it’s not applicable for earnings product.
    22. **Claim Expiry prd (Months): –** The period within which the policy holder is expected to make a claim.
    23. **Quote Expiry Prd (Days):** - The period within which a quote can be converted to a policy.
    24. **Unit rate Applicable:** - Select yes if the one is allowed to input unit rates at underwriting level.
    25. **Applicable lapse type**: - Mode used to lapse i.e. premium only or O/S schedules
    26. **Minimum Multiple of earnings**: - Used for earning products to define minimum multiple of earnings allowed
    27. **Expected schedule receipt date**: - Date when schedules are expected periodically
    28. **Auto generate policy number: -** Select Yes if policy number will be autogenerated by the system based on the set number formats.
    29. **Extension allowed**: - Indicate whether allowed in the event that one wants to postpone renewal
    30. **Renewal allowed**: - Product is renewable
    31. **Schedule adjustment period**: - Period allowed for one to provide corrections on a given schedule
    32. **Profit Share Rate**: - Rate applicable for-profit share computation
    33. **Max Extension period**: - Max days allowed for one to extend cover
    34. **Add/Ref Premium**: - For initial schedule endorsement the allowed add/Ref premium on calculating detailed member premium
    35. **Minimum FCL Members**: - Minimum number allowed for free cover limit
    36. **FCL Max amt**: - Maximum Free cover limit allowed
    37. **FCL Factor \> FCL members**: - Factor applied when members are greater than minimum
    38. **FCL Factor \< FCL members**: - Factor Applied when members are less than minimum allowed
    39. **Remarks**: - Brief description of the products and its benefits
    40. **Policy Document Name**: - Used to define the policy document name for ease in retrieval from the document folder
    41. **Receipting mode**: - select whether you receipt against a debit note or you receipt on policy (cash and carry).
    42. **Status**: - Whether product is active or not.
    43. **Medical Grace period (days)**: - Period within which members with sum assured above FCL are supposed to go for medical tests.
    44. **Catastrophe claims limit**: - maximum number of claims you can make in case of a catastrophe.
    45. **WEF**: - Effective date of the product
    46. **Product organization**- Used to capture the organization the product falls in.
    47. **Pay Multiple payees for main cover**: - Specify whether at claim processing you can pay more than one payee.
    48. **Investment rider allowed**: - Select Yes since its applicable for this product.
    49. **Investment type** – Select the investment type. In this case select *Interest Allocated*.
    50. **EMV calculation type**: - To specify Estimated maturity value calculation type.
    51. **Surr allowed**? – select whether surrender is allowed. Select *NO.*
    52. **Partial Withdrawal -** To capture partial withdrawal details.

![](media/6358a79846094c7994a36980363c9d36.png)

1.  **Death acceptable number: -** Used to set allowed claim experience per product

![](media/85999d1b62d56d0f785d15be7684c98a.png)

1.  **Premium Fractions: - Annual premium rates factors & Monthly premium rates factor**: - Used to convert annual or monthly rates to the desired premiums based on the frequency of payment

![](media/89f3c8b655400aba214d87dcd4c0f65b.png)

1.  **Schedule reports**: - Used to define schedule reports for a specified product.

![](media/383561b80d2ed4377552793f3ebdd727.png)

1.  **Lapsation**: - Used to define lapse period based on frequency of payment.

![](media/c4e69b7e00a27b3c252c18530d348245.png)

1.  **Policy documents**: - Used to define standard policy documents generated for the specified product

![](media/44afd762e14ba42d3509059fe1f4d678.png)

1.  **Product Exceptions:** - Notification to be provided in case of condition set for age and sum assured

![](media/a6d157819c58804c63fbaf2f634e6e2e.png)

1.  **Product Experience rate:** - used to capture the maximum claim experience (Experience TLR) ratio at renewal for existing clients over a specified period (Experience Period)

![](media/930acddec604b34f34c3799ccba99cb7.png)

### Relation & dependents Type

**Loaded through initial data script**

This screen is used to define relation and dependents types commonly used in life insurance

Select **relation types** from the **U/W and Quotations Setup** of the **Setup Module**

The screen below appears

![](media/4d15032dfd21b9573259ba3bf72f4024.png)

1.  To enter a new relation type, click ![](media/5516b5a56dbcf62e90f2d8a6db424f7a.png) under the relation types tab, the screen below appears

![](media/c1f06b6183db4306632174b30e9096ff.png)

1.  Enter the ID and the description of the of any expected relation types for the beneficiaries
2.  To enter Dependent types, click new under the dependent types tab. This is for dependants allowed cover alongside the life assured i.e. Spouse, child
3.  The screen below appears

![](media/baea64b768c5684e6cc4a6c30fbbf10f.png)

1.  Enter the dependent short description ID and Description

### Cover types definition

This screen is used to capture details for all **product premium items**

1.  Select **Cover types** from the **U/W & quotations setup** menu item of the **Setup Module**
2.  The screen below appears

![](media/8f6d379a477b93add59b459138902f1a.png)

1.  Click on ![](media/33cbf23d7560a8e905b102f900ac5ea1.png) to enter a new cover type, the screen below appears

![](media/b1a84a952eb52156f7dec6c1aa65e052.png)

1.  Enter the cover details
-   **Cover ID** - Cover code
-   **Cover Description** - cover type name
-   **Main Cover/Rider** is used to identify whether the cover type is the main cover or a rider.

NB: If the rider sum assured is a percentage of the main cover select *Rider (% of main cover).*

-   **Maximum age** used to indicate the maximum age for a cover type if it differs from that defined at the product level.
-   **Duration Type** represents the cover period. If period is for as long as the member is on cover then select **open** otherwise for covers that are renewed every year select **Annual**
-   **Multiplier** is used to capture the rate applied on the basic SA or basic rate to load or discount the cover type’s SA or rate. The **Division factor** is what is applied to the multiplier
-   **Read from** stands for the rates used in premium computation if stored in a tabular form then select **tables** otherwise pick **other rates**
-   **Rate type** stands for whether the rates used are **monthly rates,** **annual rates or the cover type has both** i.e. For group earnings we use Annual.
-   **Report Name: -** Report generated at policy document when the rider is attached
-   **Pay Beneficiaries**: - Specify whether you can pay beneficiaries at claim processing for this cover.
-   **Occupational benefit** *(Y/N)***: -** specifies whether a cover is occupational benefit payable in the event of death or disability caused at the work place.
-   **Claim max inst. payable:** -Specifies the maximum instalments for claims under the covered. E.g. For dismissal cover once can recover a maximum of six instalments.
-   **Claim waiting period:** - Specifies the maximum period on which the member has to wait after the policy effective date before claiming on the given cover
-   **Constant SA** *(Y/N)* **-** To specify if the cover a constant SA
-   **Constant SA Amt -** Specifies the SA if above (Constant SA) is Y

### Product Cover types

This screen is used to attach cover types to specified products

1.  Select **product cover types definition** from the **U/W & quotation setup menu** item of the **Setup** the screen below appears

![](media/732b5baeac1102d4c241fbbb4eeea4d0.png)

1.  Select the product, and click ![](media/c1a3154cebfb82ddcf11a0a446b0c793.png), the screen below appears

![](media/b75cdd6d32afa4ada094a7cc1176f216.png)

1.  Select the cover type attach from a list of values
2.  The details to be captured at this point are those that apply at cover type level based on the product selected
-   **Max Assureds**: The maximum number of people covered
-   **Max Age**: The maximum age allowed for the cover type
-   **Formulae**: For products with premium computation formulae (rate \* SA/div factor). use default rate type
-   **Refund Formulae**: Refund formulae for group products – (rate \* SA/div factor). use default rate type.
-   **% of Main/Yr Earn**: For determining SA for a rider based on basic SA.
-   **Max SA**: Maximum SA allowed
-   **Rates depend on Class of life**: Show those cover types whose rate depends on occupation classes
-   **Built In**: Shows the riders whose premium rate is taken care of in the main cover premium rate
-   **Mandatory: -** The cover type appears on all policies for the selected product
-   **Accelerator:** - The cover type once settled at claims the Sum assured for Main cover is reduced by the settled amount
-   **Group & Single Rate:** - Use of group rates or individual rate per member
-   **Apply 13th Month-** Used for clients who issue bonuses at the end of the year and would like to be covered by the policy.

Attach applicable cover types to the product you created above.

### Product Cover Types Dependants

This screen is used to define **Cover dependants** and their **cover limits**

1.  Select **Product cover type dependants** under the **U/W and quotation setup** of the core setup
2.  The screen below appears

![](media/727658c45b57756ed69ad4ad5ded9882.png)

1.  Select the product and cover type, click ![](media/99864c1d9e2908daa70bbb0da4e11095.png) to define the dependants, the screen below appears

![](media/5643b34be010bd1a3c11045b0269d2e2.png)

1.  Specify the Dependant type, maximum allowed for cover, minimum age, maximum age, minimum sum assured and maximum sum assured allowed.

## Rates Setup

### Premium Structures (Premium Masks)

This screen is used to allocate **premium profiles** to a product for easy reading of the premium rates

-   Select **premium mask** from the **U/W & Quotation rates setup** of the **Setup module**, the screen below appears

![](media/a532738e3c16769858861bb372819be5.png)

-   Select the **product** and click on ![](media/13a7b3db86546ad37422700e832277c7.png), the screen below appears

![](media/3c2135a91f9db75eabd774a65553e575.png)

-   Enter the details as indicated by the fields. ID, description, rate type and select whether it’s the default mask.
-   Rate types include:
-   Gross rates
-   Pure Rates
-   Mortality Rates
-   Risk premium rates
-   Click on save

### Premium Rates Loading

Used to define loadings for pure rates

-   Select **premium rates loading** from the **U/W & Quotation rates setup** of the **Setup module**, the screen below appears

![](media/7e8c22245ae054232be1896d66fffb21.png)

### Premium Rates

This screen is used to capture the **Group premium rates** setup based on premium mask, cover type dependant, life classes, & age next birthday

1.  Select **premium** **rates** from the **U/W and Quotations rates setup** of **the Setup**, the screen below appears

![](media/fd76222aad37601a159e814bab9f20ac.png)

1.  Select the **product**, the **applicable premium mask**, the **cover type dependant** and **life class.**
2.  Use the ![](media/333940476225a0b809df79b0c8cd2987.png) to add premium rate or the **Browse** to import the premium rates from a CSV template. The screen below appears:

![](media/d4458dbefba03694e266890ebd46d9cb.png)

Fill in the required fields**:**

1.  **ANB from/To –** age range
2.  **Range From/To –** sum assured range
3.  **Rate –** to capture monthly rates
4.  **Annual rate –** Annual rates
5.  **Single rate – Single payment rate**
6.  **Rate description –** division factor applied to the set rate
7.  **Division factor –** auto populates depending on what you have picked under rate description
8.  **Rate type** – Select the rate type
-   **Fixed rate**: Rate applies across all amounts**.**
-   **Recurring**: The rate is defined for different amounts
-   **Range (Abs):** It is where the amount payable is defined per amount range e.g. 0-10,000 rate applicable is 10%.
-   **Range (step): -** It is where the rate keeps on increasing as the amount increases i.e. for a range of 0-15,000 the rate applicable is 8%, 15,001-25,000 is 10% and so on.
1.  **Prorated/Full –** specify whether the rates are full or prorated
2.  **Multiplier rate -** is used to capture the rate applied on the basic rate to load or discount the rate. The **Division factor** is what is applied to the multiplier
3.  **Constant -** is used to capture a constant applied on the basic rate to load or discount the rate. The **Division factor** is what is applied to the constant.
4.  **Premium applicable at –** specify whether the rate is applicable at normal or refund. Select normal for the earnings product.
5.  **Gender –** specify the gender
6.  **WEF –** specify the date the rate takes effect
7.  Repeat the procedure by selecting all the applicable products, masks, cover type dependant and life class

### Free Cover Limit Tables

1.  Select **Free Cover Limit Factors** from the **U/W and Quotations rates** setup of the **Setup** module, the screen below appears
2.  Select the product and click on ![](media/54453f50ed94bb103011210cf1ddccda.png) to add new free cover limit factor

![](media/99c6dd7fd5d1a7104791bf1ba3985e89.png)

### Interest rates

Used to define interest rates used for the investment rider i.e. Estimated maturity value interest.

Select **Interest Rates** from the **U/W and Quotations rates** setup of the **Setup** module, the screen below.

Click on the general interest rates.

![](media/ca4886c75e0a6a94a9b82641fb3a3e06.png)

To add a new interest rate, click on the ![](media/9d6a3b2086affe3f2a59950da57a5079.png) screen below appears

![](media/444d2257b39a7f6e7768773be9b2b4bf.png)

Select the interest type and enter details

### Discount types

Used to capture different discounts types and respective rates applicable at u/w

![](media/0b60bc99dd212b81c739a7439f333e92.png)

-   To add a new discount, click (**+ ADD).**
-   The screen below appears (and fill in the details as shown):

![](media/416fdf4aab37bed7af6322ec2ff265a2.png)

### Loading types

Used to capture different discounts types and respective rates applicable at u/w

![](media/59dfe8d8fb6bb242231d7167ba99f992.png)

-   To add a new discount, click (**+ ADD).**
-   The screen below appears (and fill in the details as shown):

![](media/a10f14885a1dd995dfa1901cfb918aa9.png)

### Claim experience

Used to capture the claim experience rate applied on the premium rates at u/w

![](media/bf35f09093d6e84f46e1cbd884d21be6.png)

To capture a new rate click **(+ ADD).**The following screen pops up **:**

![](media/feb928d41b740640b166fb21b9d460a2.png)

-   **Class**:- The class of the claim experience( ie. Is it in class 1)
-   **Claim Exp .Rate from** *(Percentage)*:-The minimum claim experience in the given class
-   **Claim Exp .Rate from***(Percentage)*:- The maximum claim experience in the given class
-   **Claim Exp Class Rate** *(Percentage):-*The rate applied to premium rates for members who fall under this class

### Short term rates

The rates used to calculate premium retained at policy cancellation by the client

![](media/9db1ab95bdd3b45acabb9d73b908cda4.png)

To add click **(+ ADD).The following window pops up:**

![](media/3693b1ec76e5af81a5fd885ca9cf7406.png)

-   **Rate : -** The rentention premium rate
-   **Rate Division factor***(Percent,per mile)* **: -**  The division factor of the rate
-   **Period from** *(Months)*: - The start month for the application for a given premium retention limit
-   **WEF** :- The start date of the given rate
-   **WET :** - The end date of the given rate

### Profit share factor

Used to define the profit share in the case where the agent and the client are sharing in the profits. Only applicable to certain policies

![](media/814de7765520674f531d9953626d44d0.png)

To add a new click  **(+)** .The following window pops up:

![](media/0db7c9216b02686102bf9a6496b3f2b3.png)

-   **Claim Range From**: - The minimum claim experience (%) from where a certain profit share rate is applicable
-   **Claim Range To**: - The maximum claim experience (%) from where a certain profit share rate is applicable
-   **Client Share**(Percentage): -The percentage of the client’s share in the profits declared
-   **Agent Share**(Percentage): -The percentage of the agent’s share in the profits declared

### Tax types

This screen is used to define the different tax types in the individual life insurance

1.  To view the screen, click on the **Setup** module select the **Tax Types** submenu from the **Tax Definition** menu item. The screen below is opened

![](media/53d1d3e22ee5ec65cc708fb0a64d5438.png)

1.  Click on the New Button to enter new tax details i.e. **Tax ID** and **description as shown below**

![](media/d10bea31530d21ba4022a03a3f10623f.png)

1.  Select the **type** and **applicable** levels which is the point where the tax is computed

### Tax rate by product tax type

This screen is used to define **tax rates** by **product type.** This screen should only be used for taxes that apply to a specific product.

1.  To view the screen, click on the **Setup** module select the **Tax Rates by Product Tax Type** submenu from the **Tax Definition** menu item. The screen is as shown below.

![](media/f61ac358c086e1d2e0a7af4fa3395acd.png)

1.  Select the applicable at product level type, if yes select the product
2.  Click on New at Tax Rates, enter the **tax rates** for the selected **tax type** and **product type**
3.  **Range from and Range to**: - for rates that vary with Sum assured
4.  **Age from and Age to**: - Rates that vary with Age else put 0 to 99
5.  **Applied**: - Whether Sum Assured or Premium
6.  **Application Frequency**: - Whether is once or every time the transaction is done
7.  **Tax Duration**: - Period for applying the tax
8.  **Frequency of payment**: - For rates that vary with frequency of payment
9.  Specify the rate type
    1.  **Fixed**: - Rate applied on SA assured
    2.  **Recurring**: - Rate applied per specified range and any amounts thereof
    3.  **Step Range**: - Rate applied based on range of SA i.e. 1st 50000 rates of 2.5, 2nd 50000 rates of 3.5, 3rd 50000 rates of 4.5, rest 5.5
    4.  **Step absolute**: - Rate is selected based SA assured i.e. the absolute amount

### Life Premium Commission Rates Definition

This screen is used to determine the commission rates that apply to the different agents in the system.

1.  To view the screen, go to the **Core Setup** module select **commission rates definition** from the **Agent, broker and reinsurance** menu item submenu.

![](media/1f6c366c222db751e4ede3097561c162.png)

1.  Select the **product** and the **agent type**.
2.  At Special Rates define the **Rate type,** by clicking on New Button, the **Default rates** are the rates shared by all agents defined under the selected agent type. Any other **rate type** can be defined for agents who have special commission rates defined

![](media/d9ad51d60dda538bf73c299616f90ae2.png)

1.  Select the **life commission rates tab**; click on the New Button to enter the commission rate, the description; either by percent, per mille, per amount or other (you have to specify in the division factor column for this option)
2.  Division Factor
3.  Specify the rate type
    1.  **Fixed**: - Rate applied on SA assured
    2.  **Recurring**: - Rate applied per specified range and any amounts thereof
    3.  **Step Range**: - Rate applied based on range of SA i.e. 1st 50000 rates of 2.5, 2nd 50000 rates of 3.5, 3rd 50000 rates of 4.5, rest 5.5
    4.  **Step absolute**: - Rate is selected based SA assured i.e. the absolute amount
4.  Specify the **Year No from** and the **Year No to** with respect to the commission rates that apply to each year of premium settlement.
5.  Specify the beginning and the end of the policy term on the columns **policy term from** and **policy term to**.
6.  The **Wef** (With effect from) column specifies the date the policy will come to effect. Therefore, this commission rates will only be applied to policies within the specified date.

## Medicals Setups

### Medical Tests

This screen is used to capture medical tests details

Select **Medical Test** from the **Medical Test Definition** setup of the **Setup** module, the screen below

![](media/a46e6ef122d05e2bdef1aec8f9f218ef.png)

Select the **Currencies and then Medical tests** submenu across, click on ![](media/105a1c0fd3d9fddb68b4b2e5742499d3.png) to add new medical test.

The screen below appears

![](media/8edba52c621dc8a9d507911a101601e0.png)

1.  Enter the **medical description,** **pre-set medical fee, WEF & WET dates and validity period**

### Facilitator Specific Test Rates

Used to define facilitator specific tests

Click on the facilitator tab, click on the LOV ![](media/baf10d43ac2edfd398d3cc060e19d1af.png) to select the facilitator to update medical test fee.

![](media/4e6ed549c0b85bfd4e410a121de6f6e9.png)

Click on ![](media/03c33252746a51ab86c14f3085d26054.png) to attach a medical test with different fees from the standard rates

### Medical Groups

This screen is used to classify the medical tests into groups

-   To view the screen, click on the **Setup** module under the **Medical test definition** menu select the **medical test groups** option
-   The screen below appears

![](media/a74a1f198c00f0e9e5b621b9ee027036.png)

-   Click currencies and on ![](media/3e028c30ecc196a8a6d7dba46b08daac.png) under **medical test grouping** to capture a new group

![](media/f2f67d6320ddd00a3d99de7a40fa3c09.png)

-   Select a group under test group and click on ![](media/3e028c30ecc196a8a6d7dba46b08daac.png) under group test items to attach the Medical tests

![](media/07759780c535f22395cb9bf0a1a36b84.png)

Click on Save to update the record

### Medical requirements

1.  To view this screen, click on the **Setup** menu on the Medical test definition select the **medical requirements** option. The screen below appears

![](media/a7bb70a242afad89db03010f94d26c62.png)

To define a new age range, click on the given currency under currencies and across under requirements, select the product applicable ![](media/32f99139a5475d75cf73b5c5b9c2d8aa.png) the screen below appears

![](media/76ba99379a6642f6338567858c778a81.png)

1.  Highlight the medical ANB range, click on ![](media/32f99139a5475d75cf73b5c5b9c2d8aa.png) button at **requirements** and Enter the Range from and to, which is sum assured, select the medical group then click ok to **save the record,**

![](media/6d1f8bb803dc7ba69fb8df9952010445.png)

1.  Repeat the process until all requirements for the select age range are captured

### Provisions

Used to set up clauses and exclusion i.e. HIV, suicide etc

1.  To view this screen, click on the **Setup** menu on the **Medical test definition** select the **Product Provision** option. The screen below appears

![](media/a3f8809c4df77fe2e76d35127c85ef8e.png)

Select the product, click on the **provision details tab**, and click on ![](media/9027c14895a6954de9b534bf5387b932.png) at the provisions to add a new provision.

![](media/2fa195686bdbbfca1b16c96f4b652664.png)

#### Product Provision

This is used to attach the provisions defined to specific products

Select the product, click on the **Product provision details tab**, select the cover type and click on ![](media/9027c14895a6954de9b534bf5387b932.png) at the provision to attach the provision.

![](media/f1de1ee93b27379f51196ab28fe32396.png)

## Reinsurance Setup

This menu item is used for the setup of reinsurance details i.e. treaty types, treaty arrangements

### Treaty Types & Treaties

1.  To view the screen, click on the **Setup** module select the **Treaties** submenu from the **reinsurance definition** menu item

![](media/eab4363d4b9f32ea4a50595ac6203c5b.png)

1.  For the defined types define the **treaty groups**.

### Treaty Setup

This screen is used to setup the **treaty arrangement** for a given **product** for a given **year**

1.  To view the screen, click on the **Setup** module select the **Treaty Setup** submenu from the **reinsurance definition** menu item
2.  The screen below appears

![](media/85601d0269f59d2618b101dcd7b2fe2d.png)

1.  To create a new **treaty arrangement** by clicking on **![](media/50d2546bda4ebe6fce1b7e384c8e32ad.png) under treaties**. The screen below appears. Enter the details as shown below and click ok to save the record

![](media/62e492ed160affee9038a37d421f6675.png)

-   ID of the treaty arrangement
    -   Description of the treaty arrangement
    -   **Type** stands for whether the arrangement is based on the:
    -   **Underwriting year** i.e. cede to the treaty based on the year the policy was incepted. The policy is covered by one treaty until maturity.
    -   **Clean Cut**: - Cede to the current treaty irrespective of when the policy was incepted. The risk from policies is passed on to the new arrangement.
1.  Highlight the defined Treaty Arrangement, click on New at the **arrangements** **details** block to define the underwriting year

![](media/43d2251e523cf7a76cd4d6e7ac6d9c2f.png)

1.  Define the **underwriting year** and click ok to save
2.  Highlight the Underwriting year then select the **product** at the **classes of business tab. Save the record**

![](media/1ea79a4a7e650c2e838a588f1699e098.png)

1.  Highlight the product, click on the add button at product cover types tab to attach the product cover types reinsured under the specified arrangement.

![](media/3fc34155ae125b85e7e41e576603f568.png)

1.  Attach the cover type, indicate the insurer’s retention limit
2.  Indicate the amount over which to cede to avoid small ceding
3.  Indicate whether the risk is reinsured on **reducing balance** or **OS balance tables** or **constant SA**
    1.  **Reducing balance: -** Decrease proportional to OS term of cover
    2.  **OS balances tables:** - Tables used to provide rate of OS balance
    3.  **Constant SA:** - Reinsure same amount throughout cover period
4.  Attach **outstanding balance table** if risk is reinsured on **OS balance tables**
5.  Select the **treaty setup tab,** the screen below appears

![](media/ccfc6feed4cf06c9945603318d73a412.png)

1.  Click on the New button at the top to define a new treaty for the highlighted year.

![](media/ba404e695d884b207a04db391150408d.png)

1.  Click in the Period from field the **treaty arrangements dates** are picked by default from January to December of the specified year
2.  Specify all the details required click ok to save
3.  Click on the lower New button to attach the participants who should be attached at the **Agent, Broker and reinsurance screen** in **Core Setup**

![](media/48efd05ce3c9474c88912db8d5e14fec.png)

1.  Select the **treaty cover types,** the screen below appears

![](media/291c1e26c0aa9ea485a92c4ec1cd3015.png)

1.  At the **Arrangement cover types** click on New and select the cover types for the product specified
2.  Select the **cede type** i.e. Lines, percentage
    1.  **Lines**: - Specified for surplus treaty
    2.  **Percentage**: - Specified for Quota share treaty
3.  Indicate the **cede rate** based on the **cede type**
4.  Select the **rate type** i.e.
1.  **R/I rate** **Tables** for those with rate tables from the reinsurer
    1.  **Premium rates** for those on **original term basis**
    2.  **Cession rates** for those whose **cede rate** is specified as a **percentage**.
1.  **Rate name** is used to specify the Reinsurance rate tables for the cover types whose rate type is **R/I rate table**
2.  **Limit**: - Used to specify the maximum cession amount allowed for the treaty
3.  Highlight the cover type defined Click on the **Commission rates add button**
4.  ![](media/c1ed6ffbe7cc682ec69149f9fcc8e415.png) Define the commission rates per cover type

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
