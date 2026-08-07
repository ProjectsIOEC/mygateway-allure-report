# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: features\createAccount.feature.spec.js >> Create Account >> Customer is on gateway to create a new account
- Location: .features-gen\features\createAccount.feature.spec.js:6:7

# Error details

```
Test timeout of 30000ms exceeded.
```

```
Error: locator.click: Test timeout of 30000ms exceeded.
Call log:
  - waiting for locator('iframe[name="a-6aksgnyri91x"]').contentFrame().getByRole('checkbox', { name: 'I\'m not a robot' })

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - region "We value your privacy" [ref=e2]:
    - generic [ref=e3]:
      - generic [ref=e5]:
        - heading "We value your privacy" [level=2] [ref=e6]
        - generic [ref=e7]:
          - paragraph [ref=e9]: We use cookies to enhance your browsing experience and analyse our traffic. By clicking "Accept All", you consent to our use of cookies.
          - generic [ref=e10]:
            - button "Customise" [ref=e11] [cursor=pointer]
            - button "Reject All" [ref=e12] [cursor=pointer]
            - button "Accept All" [ref=e13] [cursor=pointer]
      - generic [ref=e16]:
        - text: Powered by
        - link "Visit CookieYes website" [ref=e17] [cursor=pointer]:
          - /url: https://www.cookieyes.com/product/cookie-consent/?ref=cypbcyb&utm_source=cookie-banner&utm_medium=fl-branding
          - img [ref=e18]
  - generic [ref=e31]:
    - generic [ref=e32]:
      - generic [ref=e33]:
        - generic [ref=e34]:
          - img [ref=e37] [cursor=pointer]
          - link [ref=e39] [cursor=pointer]:
            - /url: /
            - img [ref=e40]
          - button "Hello, sign in or create account" [ref=e41] [cursor=pointer]:
            - img [ref=e43]
            - generic [ref=e45]:
              - generic [ref=e46]: Hello, sign in
              - generic [ref=e47]: or create account
        - generic [ref=e48]:
          - generic [ref=e49]:
            - generic [ref=e51] [cursor=pointer]:
              - text: Shop by department
              - img [ref=e53]
            - generic [ref=e58] [cursor=pointer]:
              - img [ref=e61]
              - textbox "What are you looking for?" [ref=e64]
            - generic [ref=e76]:
              - link [ref=e77] [cursor=pointer]:
                - /url: /shopping/cart
                - img [ref=e79]
              - generic:
                - generic: Shipping Options
                - link "View Cart (0 items)":
                  - /url: /shopping/cart
                - link "Checkout":
                  - /url: /shopping/checkout
          - generic:
            - generic:
              - generic:
                - generic:
                  - generic:
                    - generic:
                      - generic:
                        - generic:
                          - button "Choose Sourcing Point":
                            - generic: Choose Sourcing Point
                            - generic:
                              - img
                              - img
                              - img
                              - img
                              - img
                              - img
                              - img
          - generic [ref=e85]:
            - generic [ref=e86]:
              - generic [ref=e87]: Add to Cart
              - button [ref=e88] [cursor=pointer]:
                - generic:
                  - img
            - generic [ref=e89]:
              - img
              - generic [ref=e91]:
                - generic [ref=e92]:
                  - progressbar "loading" [ref=e94]
                  - progressbar "loading" [ref=e96]
                - progressbar "loading" [ref=e99]
                - progressbar "loading" [ref=e102]
      - generic [ref=e107]:
        - generic [ref=e109]:
          - progressbar "loading" [ref=e112]
          - generic [ref=e113]:
            - progressbar "loading" [ref=e115]
            - progressbar "loading" [ref=e117]
            - progressbar "loading" [ref=e119]
            - progressbar "loading" [ref=e121]
        - generic [ref=e123]:
          - progressbar "loading" [ref=e126]
          - generic [ref=e127]:
            - progressbar "loading" [ref=e129]
            - progressbar "loading" [ref=e131]
            - progressbar "loading" [ref=e133]
            - progressbar "loading" [ref=e135]
        - generic [ref=e137]:
          - progressbar "loading" [ref=e140]
          - generic [ref=e141]:
            - progressbar "loading" [ref=e143]
            - progressbar "loading" [ref=e145]
            - progressbar "loading" [ref=e147]
            - progressbar "loading" [ref=e149]
        - generic [ref=e151]:
          - progressbar "loading" [ref=e154]
          - generic [ref=e155]:
            - progressbar "loading" [ref=e157]
            - progressbar "loading" [ref=e159]
            - progressbar "loading" [ref=e161]
            - progressbar "loading" [ref=e163]
        - generic [ref=e165]:
          - progressbar "loading" [ref=e168]
          - generic [ref=e169]:
            - progressbar "loading" [ref=e171]
            - progressbar "loading" [ref=e173]
            - progressbar "loading" [ref=e175]
            - progressbar "loading" [ref=e177]
        - generic [ref=e179]:
          - progressbar "loading" [ref=e182]
          - generic [ref=e183]:
            - progressbar "loading" [ref=e185]
            - progressbar "loading" [ref=e187]
            - progressbar "loading" [ref=e189]
            - progressbar "loading" [ref=e191]
        - generic [ref=e193]:
          - progressbar "loading" [ref=e196]
          - generic [ref=e197]:
            - progressbar "loading" [ref=e199]
            - progressbar "loading" [ref=e201]
            - progressbar "loading" [ref=e203]
            - progressbar "loading" [ref=e205]
        - generic [ref=e207]:
          - progressbar "loading" [ref=e210]
          - generic [ref=e211]:
            - progressbar "loading" [ref=e213]
            - progressbar "loading" [ref=e215]
            - progressbar "loading" [ref=e217]
            - progressbar "loading" [ref=e219]
    - img [ref=e225]
    - generic:
      - generic:
        - generic:
          - generic:
            - generic:
              - generic:
                - generic:
                  - generic:
                    - generic:
                      - generic:
                        - generic:
                          - generic:
                            - generic:
                              - generic:
                                - img
                      - generic:
                        - generic: Hi, Sign In
                        - generic: Create an account
                  - generic:
                    - generic:
                      - generic:
                        - generic:
                          - img
                      - generic: Home
                  - generic:
                    - generic:
                      - generic:
                        - generic:
                          - img
                      - generic: Sign In
    - generic [ref=e231]:
      - button [ref=e232] [cursor=pointer]:
        - generic:
          - img
      - generic [ref=e236]:
        - heading "Create Account" [level=2] [ref=e237]
        - generic [ref=e239]:
          - textbox "Full name" [ref=e240]: Test Customer
          - textbox "Email" [ref=e241]: testcustomer@email.co.za
          - combobox [ref=e242]:
            - option "Afghanistan" [selected]
            - option "Albania"
            - option "Algeria"
            - option "Andorra"
            - option "Angola"
            - option "Antigua and Barbuda"
            - option "Argentina"
            - option "Armenia"
            - option "Australia"
            - option "Austria"
            - option "Azerbaijan"
            - option "Bahamas"
            - option "Bahrain"
            - option "Bangladesh"
            - option "Barbados"
            - option "Belarus"
            - option "Belgium"
            - option "Belize"
            - option "Benin"
            - option "Bhutan"
            - option "Bolivia"
            - option "Bosnia and Herzegovina"
            - option "Botswana"
            - option "Brazil"
            - option "Brunei Darussalam"
            - option "Bulgaria"
            - option "Burkina Faso"
            - option "Burundi"
            - option "Cabo Verde"
            - option "Cambodia"
            - option "Cameroon"
            - option "Canada"
            - option "Central African Republic"
            - option "Chad"
            - option "Chile"
            - option "China"
            - option "Colombia"
            - option "Comoros"
            - option "Congo"
            - option "Congo, Democratic Republic of the"
            - option "Costa Rica"
            - option "Côte d'Ivoire"
            - option "Croatia"
            - option "Cuba"
            - option "Cyprus"
            - option "Czechia"
            - option "Denmark"
            - option "Djibouti"
            - option "Dominica"
            - option "Dominican Republic"
            - option "Ecuador"
            - option "Egypt"
            - option "El Salvador"
            - option "Equatorial Guinea"
            - option "Eritrea"
            - option "Estonia"
            - option "Eswatini"
            - option "Ethiopia"
            - option "Fiji"
            - option "Finland"
            - option "France"
            - option "Gabon"
            - option "Gambia"
            - option "Georgia"
            - option "Germany"
            - option "Ghana"
            - option "Greece"
            - option "Grenada"
            - option "Guatemala"
            - option "Guinea"
            - option "Guinea-Bissau"
            - option "Guyana"
            - option "Haiti"
            - option "Honduras"
            - option "Hungary"
            - option "Iceland"
            - option "India"
            - option "Indonesia"
            - option "Iran"
            - option "Iraq"
            - option "Ireland"
            - option "Israel"
            - option "Italy"
            - option "Jamaica"
            - option "Japan"
            - option "Jordan"
            - option "Kazakhstan"
            - option "Kenya"
            - option "Kiribati"
            - option "Korea, Democratic People's Republic of"
            - option "Korea, Republic of"
            - option "Kuwait"
            - option "Kyrgyzstan"
            - option "Lao People's Democratic Republic"
            - option "Latvia"
            - option "Lebanon"
            - option "Lesotho"
            - option "Liberia"
            - option "Libya"
            - option "Liechtenstein"
            - option "Lithuania"
            - option "Luxembourg"
            - option "Macao"
            - option "North Macedonia"
            - option "Madagascar"
            - option "Malawi"
            - option "Malaysia"
            - option "Maldives"
            - option "Mali"
            - option "Malta"
            - option "Marshall Islands"
            - option "Mauritania"
            - option "Mauritius"
            - option "Mexico"
            - option "Micronesia"
            - option "Moldova"
            - option "Monaco"
            - option "Mongolia"
            - option "Montenegro"
            - option "Morocco"
            - option "Mozambique"
            - option "Myanmar"
            - option "Namibia"
            - option "Nauru"
            - option "Nepal"
            - option "Netherlands"
            - option "New Zealand"
            - option "Nicaragua"
            - option "Niger"
            - option "Nigeria"
            - option "Niue"
            - option "Norfolk Island"
            - option "Northern Mariana Islands"
            - option "Norway"
            - option "Oman"
            - option "Pakistan"
            - option "Palau"
            - option "Panama"
            - option "Papua New Guinea"
            - option "Paraguay"
            - option "Peru"
            - option "Philippines"
            - option "Pitcairn"
            - option "Poland"
            - option "Portugal"
            - option "Puerto Rico"
            - option "Qatar"
            - option "Réunion"
            - option "Romania"
            - option "Russian Federation"
            - option "Rwanda"
            - option "Saint Helena"
            - option "Saint Kitts and Nevis"
            - option "Saint Lucia"
            - option "Saint Pierre and Miquelon"
            - option "Saint Vincent and the Grenadines"
            - option "Samoa"
            - option "San Marino"
            - option "Sao Tome and Principe"
            - option "Saudi Arabia"
            - option "Senegal"
            - option "Serbia"
            - option "Seychelles"
            - option "Sierra Leone"
            - option "Singapore"
            - option "Sint Maarten"
            - option "Slovakia"
            - option "Slovenia"
            - option "Solomon Islands"
            - option "Somalia"
            - option "South Africa"
            - option "South Georgia and the South Sandwich Islands"
            - option "South Sudan"
            - option "Spain"
            - option "Sri Lanka"
            - option "Sudan"
            - option "Suriname"
            - option "Sweden"
            - option "Switzerland"
            - option "Syrian Arab Republic"
            - option "Taiwan"
            - option "Tajikistan"
            - option "Tanzania, United Republic of"
            - option "Thailand"
            - option "Timor-Leste"
            - option "Togo"
            - option "Tokelau"
            - option "Tonga"
            - option "Trinidad and Tobago"
            - option "Tunisia"
            - option "Turkey"
            - option "Turkmenistan"
            - option "Turks and Caicos Islands"
            - option "Tuvalu"
            - option "Uganda"
            - option "Ukraine"
            - option "United Arab Emirates"
            - option "United Kingdom"
            - option "United States of America"
            - option "United States Minor Outlying Islands"
            - option "Uruguay"
            - option "Uzbekistan"
            - option "Vanuatu"
            - option "Venezuela"
            - option "Viet Nam"
            - option "British Virgin Islands"
            - option "United States Virgin Islands"
            - option "Wallis and Futuna"
            - option "Western Sahara"
            - option "Yemen"
            - option "Zambia"
            - option "Zimbabwe"
          - generic [ref=e244]:
            - textbox [disabled] [ref=e245]: "+93"
            - textbox "Phone" [ref=e246]: "123456789"
          - textbox "Comments" [active] [ref=e247]: "123456789"
          - iframe [ref=e251]:
            - generic [ref=f1e2]:
              - generic [ref=f1e3]:
                - checkbox "I'm not a robot" [ref=f1e7]
                - generic [ref=f1e11]: I'm not a robot
              - generic [ref=f1e15]: reCAPTCHA
          - button "Continue" [ref=e252] [cursor=pointer]:
            - generic [ref=e253]: Continue
        - generic [ref=e255]:
          - generic [ref=e256]: Already have an account?
          - generic [ref=e257] [cursor=pointer]: Sign in
```

# Test source

```ts
  1  | import { chromium } from '@playwright/test';
  2  | import { createBdd } from "playwright-bdd";
  3  | import { test} from "playwright-bdd";
  4  | import { LoginPage } from '../pages/LoginPage';
  5  | import { customers } from '../support/config/customers';
  6  | import { urls } from '../support/config/urls';
  7  | 
  8  | const { Given, When, Then } = createBdd(test);
  9  | 
  10 | //Create a new customer account
  11 | Given("Customer is on the gateway login page to create a new account", async ({page}) =>
  12 | {
  13 |     const loginPage = new LoginPage(page);
  14 |     await loginPage.goto(urls.dev);
  15 | })
  16 | 
  17 | When('Customer clicks Create account', async ({page}) => {
  18 |     await page.getByText('Create account', { exact: true }).click();
  19 | });
  20 | 
  21 | When('Customer enters their name', async ({page}) => {
  22 |     await page.getByRole('textbox', { name: 'Full name' }).click();
  23 |     await page.getByRole('textbox', { name: 'Full name' }).fill(customers.testCustomer.name);
  24 | });
  25 | 
  26 | When('Customer enters their email', async ({page}) => {
  27 |     await page.getByRole('textbox', { name: 'Email' }).click();
  28 |     await page.getByRole('textbox', { name: 'Email' }).fill(customers.testCustomer.email);
  29 | });
  30 | 
  31 | When('Customer enters their country', async ({page}) => {
  32 |     await page.getByRole('combobox').selectOption('AF');
  33 | });
  34 | 
  35 | When('Customer enters their phone number', async ({page}) => {
  36 |     await page.getByRole('textbox', { name: 'Phone' }).click();
  37 |     await page.getByRole('textbox', { name: 'Phone' }).fill(customers.testCustomer.phoneNumber);
  38 | });
  39 | 
  40 | When('Customer enters a comment', async ({page}) => {
  41 |     await page.getByRole('textbox', { name: 'Comments' }).click();
  42 |     await page.getByRole('textbox', { name: 'Comments' }).fill(customers.testCustomer.phoneNumber);
  43 | });
  44 | 
  45 | When('Customer clicks captcha', async ({page}) => {
> 46 |     await page.locator('iframe[name="a-6aksgnyri91x"]').contentFrame().getByRole('checkbox', { name: 'I\'m not a robot' }).click();
     |                                                                                                                            ^ Error: locator.click: Test timeout of 30000ms exceeded.
  47 | });
  48 | 
  49 | When('Customer clicks continue button', async ({page}) => {
  50 |     await page.getByRole('button', { name: 'Continue' }).click();
  51 | });
  52 | 
  53 | Then('A customer clicks button Done', async ({page}) => {
  54 |     await page.getByText('An email with reset').click();
  55 | });
  56 | 
```