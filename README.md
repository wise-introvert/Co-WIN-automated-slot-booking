# Co-WIN automated slot booking
##### _Automatically book vaccine slots on Co-WIN as and when they become available_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

This is a browser extension that aims to automatically book vaccine slots for registered beneficiaries on the [Co-WIN website](https://selfregistration.cowin.gov.in/) as per availability. Options for registration are obtained beforehand and a booking is attempted once a slot becomes available. Co-WIN uses Bearer tokens for authentication that automatically expire after 15 minutes. If a slot becomes available after a user is automatically logged out, an audio alert is sent out and the booking is continued after successful login.

## Setup

> This is dev version of the extension and needs to be set up manually.
> The setup procedure is demonstrated for Google Chrome.
> Porting to the Chrome web store is a work in progress.
> Similar procedures exist for all other webkit browsers as well.

Download the repository from [GitHub](https://selfregistration.cowin.gov.in/).

Extract the files in a directory. The location of this directory cannot change once it has been set up.

Open Google Chrome. Navigate to **More Tools > Extensions**.

Click on **Developer Mode**.

Click on **Load Unpacked**.

Browse to the directory where you extracted the files and click on **Select Folder**. Make sure you go inside the <CoWIN Automated slot booking> directory.

The extension should show up on the Extensions page.

Visit [https://selfregistration.cowin.gov.in/](https://selfregistration.cowin.gov.in/) and login using your phone number and OTP. A yellow icon should appear on the bottom right corner.

Once you have logged in, click on the icon to open the options page. Make sure you fill in all the options correctly and then click on Start to start the automatic vaccine registration process.


If you get automatically logged out and a slot becomes available, the page sends out an audio alert and prompts you to re-login. Thereafter, the vaccine booking process is completed with the already provided options after re-login.




## License

GNU General Public License v3.0