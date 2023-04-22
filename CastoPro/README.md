# CastoPro

## About the job
- **Task:** Find an error on the page
- **Page:** [CastoPro - the loyalty program for professionals (Castorama)](https://castopro.castorama.pl/pl/home)
- **Environment:** Google Chrome 110.0.5481.100 in Ubuntu 20.04.4 LTS
- **Timeframe:** 48h
- **End date:** 2023-03-01

## Additional information
- The most popular web browser was chosen due to the lack of requirements for a specific testing environment and a responsive version
- It was not clear from the description of the task whether you should test only one page with this exact address or the entire process of registering for the loyalty program
- When testing the page, I assumed it was the whole site, but I will mention that I noticed only one minor technical error on the main page

## Issues
### Main page
#### [#01: The element `<div class="container">` was not closed](/CastoPro/files/01.md)

### Registration
#### [#02: No information about required fields during registration](/CastoPro/files/02.md)

#### [#03: The registration page does not check all required fields simultaneously](/CastoPro/files/03.md)

#### [#04: The correctness of the e-mail on the registration page is validated only after entering the phone number](/CastoPro/files/04.md)

### Login
#### [#05: The login page does not check both login fields simultaneously](/CastoPro/files/05.md)

#### [#06: Two formats of login errors](/CastoPro/files/06.md)

#### [#07: Misleading error message during the password recovery when an e-mail is not in the database](/CastoPro/files/07.md)

### Responsive design
#### [#08: The paragraph `Od 25 lat wspieramy Profesjonalistów` disappears below the 992px width](/CastoPro/files/08.md)

#### [#09: The menu background is too short between 992px and 1098px width](/CastoPro/files/09.md)

#### [#10: The menu button overlaps the website logo below 284px width](/CastoPro/files/10.md)

#### [#11: Opening and closing the menu is not a button, but narrow elements](/CastoPro/files/11.md)

### Website usability
#### [#12: The regulations page does not scale below 456px width](/CastoPro/files/12.md)

#### [#13: The privacy policy page does not scale below 382px width](/CastoPro/files/13.md)
