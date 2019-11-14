## Example of Vaccine Certification Issue

This is an example of a simple personal certification issue using uPort. 

The following code was created in response to the following interview take home assignment for the position of Blockchain Developer/Consultant in the winter of 2019.

The assignment was as follows:

* Start of Assignment Document *
1. You have 24 hours from opening the WeTransfer link to
complete this assignment.
2. Upon completing the test, send a link to a repository for the
assignment, and your video link to mhydary@unicef.org &
blockchain@unicef.org.
3. The repository for the assignment should contain all the necessary
components that would allow for a larger global development team to
easily understand, test, and integrate your code into their work.
4. If we do not receive your link by the end of 24 hours from start time
(the time you open the WeTransfer link), it will not be considered.
Press send a minute or two early to be on the safe side. We will send
an acknowledgement of receipt within 24 hours.
Your 24 hours begins now.
Unfortunately, your global development team will not be able to answer any
questions…
You are on your own. :)
Congratulations - We’d like to invite you to roll up your sleeves and take the UNICEF
Innovation Challenge.
You are part of a global development team - so from the challenge below, you can
isolate one specific problem space that you can prototype in 4 hours - you should be
able to:
1. Demonstrate the ability to conceptualize the larger project but understand that
you are only solving for a specific part of it (i.e. understand that a big problem
must necessarily be broken down in to compossible, modular pieces, and that
you are only going to be able to build one of those - so build it really well)
2. Showcase your technical ability to prototype this specific slice at all levels of the
stack (there has to be enough verticality for the rest of the global team to interact
with your work - it can’t just be a small, self-contained nugget
3. Build something brilliant… you have 4 hours so push the limit on what’s been
done in your specific area. We’d rather see you take a risk that the global team
can help refine later than have you build something boring and safe
The challenge is to create a way for an individual to have valid credentials that can
transported across borders, can be accessed at any time, and updated when they have
an internet connection.
The credentials need to be accessible on a variety of devices, with limited connectivity
and verifiable by third parties. The individual credentials create a pattern/story that help
individuals create a reputation, over time, within a particular context.
There would be:
• CREDENTIAL HOLDER (the person who earned a specific credential),
• ISSUER (group/person who has the authority to assign credentials),
• AUDITOR (third party who wishes to validate a credential claim)
• THE CREDENTIAL ITSELF
Credentials are issued from an ISSUER, directly to a CREDENTIAL holder after the
successful completion of a pre-determined tasked (e.g. receiving a vaccine). Think of
this like a digital medical passport.
Some suggestions of necessary components are:
1. To create a credential as an issuer (i.e. creating a vaccine that can be issued to
an individual)
2. Issuing the certification (i.e. giving someone a credential saying they got a
vaccine)
3. Viewing the certification (i.e. an outside person can confirm that an individual has
received x vaccine)
4. Having third parties request only certain parts of your credentials (i.e. only
showing vaccines that are specific to entering a specific county)
5. A dispute mechanism / revoking ability (i.e. you need to update the expiry date of
your vaccine records)
6. Any other chunk… just define what the chunk is in a sentence like the ones
above
Pick a part of this. Make it amazing. Make it work.
Requirements:
• Ensure you have one smart contract in your solution
• Have a sketch of the UI the issuer/credential holder/auditor would use to interact
with your smart contract
• Create 3 slides summarizing your solution to showcase to the project manager
• Create a 3-4 minute video of your demo, walking us through your solution (i.e.
your slides), showing your UI sketch, and your backend (we will only watch the
first 4 minutes of any video submitted)
• Follow instructions above to send us your repository and video links
Your only constraint is time. Please limit your development time to four hours (excluding
the creation of your slides). We will expect to see your final product within 24 hours.
Good luck.
* End of Assignment Document *


## What it does
This sample code simply issues the user a Malaria Vaccine Certification. Simply, the user visits a website that requests a login via the uPort app. The website acknowledges the user's digital identity and then requests permission to issue the vaccination certificate. The user scans the certificate QR code and accepts or declines the certificate, which is now tied to the user's uPort identity.

For questions about design or why I chose uPort rather than coding everything from scratch, feel free to chat with me during the interview. :)


## How to run.
In order to run this demo / example, you need to install uPort into your mobile device.

To view/run the demo, do as follows.

1. Check out this git repository, navigate to the VaccineCredentialExample directory, and run the Certification Authority server by typing:

>node server.js

2. The application will give you a url to navigate to on your browser. Put that generated url into your navigation bar and scan the QR code with your uPort app to log in (be patient, the QR code may take a while to appear!)

3. When you scan the QR code, your mobile app will ask you to log in. When you do, the website will inform you that you have now been registered with the UNICEF Vaccine Certification Authority. It will then issue you a certification by displaying a new QR code.

4. Scan this QR code, and accept your Malaria Vaccine certification. Your certification is now tied to your uPort identity as seen in your mobile app.


## License
This demo code and all of the materials in this repository are issued out free to use under the General Public License v. 3.0