# **Unit-10 PHP Form Processing**

## 10-1:Update Form Handler

**Your assignment:**

1. Create an HTML label with the text _"Please select a subscription type."_ below the email field. 
    1. Add a set of two radio buttons to the HTML form.
    2. One radio will be have the value _"Normal"_ and the other will have the value _"Expert"_
2. Create an HTML label with the text _"Recieve special offers and latest updates?"_ below the radio buttons
    1. Add a checkbox to the HTML form and give it a text label of _"Yes"_
3. Create a label with the text _"How did you find us?"_
    1. Add an HTML select drop-down list with the following selections to the HTML form.
        1. Word of mouth
        2. Internet
        3. Podcast
4. Add Honeypot security to the form
5. Add PHP in the Model/Controller area of the page that does the following
    1. Checks if the form was submitted via the POST method
    2. Validate the honeypot security
    3. If the form was submitted and the honeypot validation passes, do the following (replace everything in `<brackets>` with the actual submitted form value)
        1. Display a Success form instead of the default intake form
        2. The success form should say
            1. _"Thank you `<first name>` `<last name>`"_
            2. Subscription Type: `<subscrition type>`
            3. Recieve Special Offers: `<special offers selection>` (Will be either _"Yes"_ or _"No"_)
            4. How you found us: `<how they found us selection>`
            5. A signup confirmation has been sent to `<email>`. Thank you for your support!
