Hi Team,

I have developed a SIN Generator & Validator Tool to assist with testing scenarios that require valid Canadian Social Insurance Numbers (SINs).
 
**Features**

✅ Generate valid SINs using the Luhn algorithm

✅ Choose the starting digit (0-9) for generated SINs

✅ Generate a single SIN or bulk SINs (up to 100 at a time)

✅ Copy individual SINs or all generated SINs with one click

✅ Validate existing SIN numbers instantly

✅ Fully client-side application. No data is stored or transmitted
 
**Access Options:**

**Option 1:** Use Online

Access the tool directly from your browser:

🔗 SIN Generator | Generate & Validate

 <img width="800" height="424" alt="image" src="https://github.com/user-attachments/assets/e7e3a31a-691d-4635-a437-a4a5844b2e6c" />

**Option 2:** Run Locally

Download the HTML file and open it in any modern browser:

🔗 sin-generator/index.html at main · itsgowrish/sin-generator

 <img width="800" height="420" alt="image" src="https://github.com/user-attachments/assets/b2b97465-c900-4177-b1a1-6054de25e78b" />

**Quick User Guide**

**Generate a Single SIN**

1) Select the desired first digit (0-9) or choose Random.

2) When Random is selected, the tool automatically generates SINs starting with 1, 2, 3, 4, 5, 6, 7, or 9, excluding:

   - 0 because a SIN cannot start with 0.
   - 8 because it has historically been associated with business/corporate numbering structures and is generally not used for individual SIN testing.

3) Click Generate SIN.

4) Use Copy to copy the generated SIN.

**Generate Multiple SINs**

1) Enter the number of SINs to generate (1-100).

2) Select a starting digit or Random.

3) Click Generate SINs.

4) Use Copy beside an individual SIN or Copy All SINs.

**Validate a SIN**

1) Enter or paste a 9-digit SIN.

2) Click Validate SIN Number.

3) The tool will indicate whether the SIN passes Luhn validation.
 
**SIN First Digit Reference**

**First Digit	Region / Category**

1-	Atlantic Provinces (Nova Scotia, New Brunswick, Prince Edward Island, Newfoundland and Labrador) or overseas assignments

2-3	- Quebec

4-5 - Ontario

6	- Prairie Provinces (Manitoba, Saskatchewan, Alberta), Northwest Territories, Nunavut

7 -	British Columbia and Yukon

9	- Temporary residents (non-citizens/non-permanent residents) with an expiry date

**Note:** Historically, SINs beginning with 8 have been associated with business or corporate numbering structures and are excluded from random generation in this tool.
 
**Why Another SIN Generator Tool?**

There are already several SIN generators available on the internet. However, this tool provides a few advantages tailored to our testing needs:

✅ Runs locally by simply opening the HTML file in a browser. No installation, setup, or internet connection is required after downloading.

✅ Internal-use friendly, making it suitable for testing scenarios where users prefer not to rely on third-party websites.

✅ Privacy-focused, as all generation and validation logic runs entirely within the browser. No data is stored, logged, or transmitted.

✅ Enhanced customization, including support for generating SINs with a specific starting digit and bulk-generating up to 100 SINs at a time.

✅ Easily maintainable and extensible, allowing enhancements based on team feedback and evolving testing requirements.

✅ Centralized access, available both as a downloadable local tool and as an online application for quick access.
 
Please feel free to use the tool and share any feedback, enhancement requests, or suggestions. Based on team feedback and future testing needs, I can continue to enhance and maintain the tool by adding new features, usability improvements, and additional validation capabilities.
 
Thanks,
Gowrisankar Chandrasekaran
