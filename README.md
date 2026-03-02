# test-da COP

*description of the COP*

**COP timeframe** 2026-02-16 - 2026-05-25

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/test-da](https://cra-proto.github.io/test-da)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-02

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(CRA Newsroom)
    node4(Get ready: the CRA is in its summertime benefit period! Banana)
    node5(New page)
    node6(Reminder - Apply by June 30 for period two of the interim Canada Dental Benefit! Ok)
    node7(Tax tips - 2024)
    node8(CRA Multimedia library)
    node9(Individuals video gallery)
    node10(Change it up: Pay your taxes online)
    node11(Payments – CRA)
    node12(Payments to the CRA)
    node13(Make a payment)
    node14(Pay with a debit card through the CRA's My Payment service – Payments to the CRA)
    node15(Forms and publications - CRA)
    node16(Canada Revenue Agency forms listed by number)
    node17(L300 Cannabis Licence Application under the Excise Act, 2001)
    node18(L300SCHA Schedule A - Other Business Location#40;s#41; #40;to support a cannabis licence application#41;)
    node19(Taxes)
    node20(Tax credits and benefits for individuals)
    node21(Canada Dental Benefit - Closed)
    node22(Canada Dental Benefit - Closed<br>If you disagree with the decision)
    node23(Canada Dental Benefit - Closed<br>Validating your application)
    node24(Canada Dental Benefit - Closed<br>Return a payment)
    node25(New page)
    node26(New page)
    node27(New page)
    node28(Canada Dental Benefit - Closed<br>Who was eligible)
    node29(Split into subway pattern)
    node30(GST/HST for businesses)
    node31(Excise and specialty taxes)
    node32(Cannabis duty)
    node33(Apply for a cannabis licence from the CRA)
    node34(Apply for a cannabis licence from the CRA<br>Eligibility conditions)
    node35(Apply for a cannabis licence from the CRA<br>How to apply)
    node36(Apply for a cannabis licence from the CRA<br>Who should apply)
    node37(Excise duties technical information)
    node38(Excise duty memoranda)
    node39(EDM6-2 Obtaining and renewing a cannabis licence)
    node40(File your GST/HST return)
    node41(Canada Dental Benefit - Closed<br>Contact us)
    node42(File your GST/HST return<br>How to file – File your GST/HST return)
    node1 --x node2
    node2 --> node3
    node3 --x node4
    node4 --x node5
    node4 --> node6
    node3 --x node7
    node2 --x node8
    node8 --> node9
    node9 --> node10
    node2 --> node11
    node11 --> node12
    node12 --> node13
    node13 --> node14
    node2 --> node15
    node15 --> node16
    node16 --> node17
    node16 --> node18
    node1 --> node19
    node19 --> node20
    node20 --> node21
    node21 --> node22
    node22 --> node23
    node23 --> node24
    node24 --x node25
    node24 --x node26
    node22 --x node27
    node21 --> node28
    node21 --> node29
    node19 --> node30
    node19 --> node31
    node31 --x node32
    node32 --> node33
    node33 --> node34
    node33 --> node35
    node33 --> node36
    node31 --> node37
    node37 --> node38
    node38 --> node39
    node40 --> node41
    node40 --> node42
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/news/newsroom.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2023/get-ready-cra-summertime-benefit-period.html" _blank
    click node5 "https://www.canada.ca/ok.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2024/reminder-apply-by-june-30-for-period-two-of-the-interim-canada-dental-benefi.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2024.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library/individuals-video-gallery.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/news/cra-multimedia-library/individuals-video-gallery/transcript-change-pay-your-taxes-online.html" _blank
    click node11 "https://www.canada.ca/en/revenue-agency/services/payments.html" _blank
    click node12 "https://www.canada.ca/en/revenue-agency/services/payments/payments-cra.html" _blank
    click node13 "https://www.canada.ca/en/revenue-agency/services/payments/payments-cra/individual-payments/make-payment.html" _blank
    click node14 "https://www.canada.ca/en/revenue-agency/services/e-services/payment-save-time-pay-online.html" _blank
    click node15 "https://www.canada.ca/en/revenue-agency/services/forms-publications.html" _blank
    click node16 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms.html" _blank
    click node17 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/l300.html" _blank
    click node18 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/l300scha.html" _blank
    click node19 "https://www.canada.ca/en/services/taxes.html" _blank
    click node20 "https://www.canada.ca/en/services/taxes/child-and-family-benefits.html" _blank
    click node21 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit.html" _blank
    click node22 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/application-denied.html" _blank
    click node23 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/validation.html" _blank
    click node24 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/return-paymelalalalalalant.html" _blank
    click node25 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/return-paymelalalalalalant/" _blank
    click node26 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/return-paymelalalalalalant/my-page.html" _blank
    click node27 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/application-denied/sd.html" _blank
    click node28 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/who-apply.html" _blank
    click node30 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses.html" _blank
    click node31 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies.html" _blank
    click node32 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/excise-duties-levies/cannabis-duty.html" _blank
    click node33 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/excise-duties-levies/cannabis-duty/apply-cannabis-licence.html" _blank
    click node34 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/excise-duties-levies/cannabis-duty/apply-cannabis-licence/eligibility.html" _blank
    click node35 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/excise-duties-levies/cannabis-duty/apply-cannabis-licence/how-apply.html" _blank
    click node36 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/excise-duties-levies/cannabis-duty/apply-cannabis-licence/who-should-apply.html" _blank
    click node37 "https://www.canada.ca/en/revenue-agency/services/tax/technical-information/excise-duty.html" _blank
    click node38 "https://www.canada.ca/en/revenue-agency/services/tax/technical-information/excise-duty/excise-duty-memoranda.html" _blank
    click node39 "https://www.canada.ca/en/revenue-agency/services/tax/technical-information/excise-duty/excise-duty-memoranda/edm6-2-obtaining-and-renewing-a-cannabis-licence.html" _blank
    click node40 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/file-gst-hst-return.html" _blank
    click node41 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/contact.html" _blank
    click node42 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/file-gst-hst-return/how-file.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node6,node10,node13,node14,node17,node18,node21,node22,node23,node24,node25,node26,node27,node28,node33,node34,node35,node36,node39,node41,node42 inscope
    classDef isnew fill:#00706f,color:#fff
    class node25,node26,node27 isnew
    classDef ismoved fill:#eab308,color:#000
    class node6,node23,node40,node41 ismoved
```
