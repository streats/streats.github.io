---
title: Discount codes in a day
---

<link rel="stylesheet" href="style.css">

## Project overview
* Client: Daye is a tampon subscription service. Customers create their custom tampon box according to their needs, and set the delivery frequency based on their cycle length. Tampons are delivered directly to their door just in time for their period.
* Project: UX design and transactional microcopy for adding discount codes to checkout flow
* Role: I designed the product logic, produced UI assets, wrote the microcopy (including all possible field states and data validation), and oversaw implementation and testing of the integration with our order management system.
* Skills: Content strategy, UX writing, UX design

## Design problem
We were asked to implement discount codes to take advantage of a promotion opportunity. The timeline to roll it out was very tight (less than 1 day) so I developed a minimum viable design that was also robust and thorough.

## Getting to the solution
While it might seem that adding a discount code field to the checkout page would be a relatively small, self-contained change, it actually had a much wider impact on the product, as it would affect every place the price was displayed: several pages in the the checkout flow, the account page where users managed their subscription and could view their billing history, transactional emails, as well as our back-office order management system.


### Field states
There were 3 possible states for the discount code field for 4 possible scenarios:

* Empty
* Valid - code successfully applied
* Invalid - code is not a valid code
* Invalid - code is expired

I designed state messages for the valid and invalid states, and created design assets in Figma to communicate to developers how these should appear. For example, emphasising errors with red field outline and error messages.

![Figma mockup of discount code fields with different states: Active (“Enter code”), Valid (“VALIDCODE”), Invalid (“FAKECODE” and “That’s not a valid code. Please try again), Invalid expired (“THINGTESTING” and “That code is no longer valid”. The CTA button for all states reads “Apply code”](https://user-images.githubusercontent.com/12902836/192862623-d44575d1-fd0f-499d-95c2-877c701c366f.png)

### Payment details screen
Step 3 of the checkout flow included both the payment details form where the discount code field would appear, and an order summary detailing the price and shipping period. This order summary also required a content change to support the discount code feature.

Most obviously, we needed to reflect the discount in the order price breakdown, which was simple enough. However, because the user was purchasing a subscription, and the discount only applied to this initial purchase, we needed to make it clear how long the discounted price would apply, when the normal price would resume, and what it would be. Since users could customise their box frequency, some subscriptions renewed every 4 weeks, others might be every 12 weeks. As such, this discount code wasn't for a fixed period of time such as the first month, so we had to make this copy variable.

![Checkout page with highlighted areas showing content changes: Discount code field added to Payment Details section, discount line item in Order Summary, and discount validity details in Order Summary.](https://user-images.githubusercontent.com/12902836/192863021-82f572d4-3acc-446e-9825-73eeecd59bfd.jpeg)

### Order confirmation page
As with the order summary, the order confirmation page was made more complex with the introduction of discounts. Once again, we needed to make it clear what today's purchase was, with discount applied, but also outline how and when prices would change once the discount code stopped being applied.

To resolve this, I added a "discount applied" label to today's price, and introduced a "future billing amounts" line item which detailed the same information as on the order summary. 

![Order confirmation page with highlighted areas showing content changes: Discount label added to “Subscription amount” and “Future billing amounts” line item added, detailing discounted price, discount validity date and normal subscription price.](https://user-images.githubusercontent.com/12902836/192863127-5929665e-82ac-4f28-8074-a515d3e80856.jpeg)

### Account page
On the account page, the "billing and payment" section included details of the next billing amount. Here again, we needed to make it clear this amount was temporary and had a discount applied.

![Subscription settings page with highlighted area of content changes to Billing & Payment section detailing discounted price, discount validity dates and normal price.](https://user-images.githubusercontent.com/12902836/192863304-2dc3c4d9-f930-42d8-9241-390bdc2e8f66.jpeg)

## Project outcome
After implementing content changes across the product, emails and tooling, I put together a test plan to QA the discount code functionality and associated content changes. Working mainly with Engineering, as well as colleagues from other teams who volunteered to help test to meet the tight delivery deadline, we rigorously tested various scenarios on the checkout page (valid and invalid) and verified the price throughout all touchpoints throughout the webapp, order system and emails. 

We successfully launched discount codes approximately 13 hours after being given the brief (the next afternoon). 
