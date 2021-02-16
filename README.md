[![Build Status](https://travis-ci.com/carpentries/workshop-template.svg?branch=gh-pages)](https://travis-ci.com/carpentries/workshop-template)



R plotting with ggplot2 workshop, Macquarie University, Feb 2021

Workshop held online using Zoom

Workshop website: https://mq-software-carpentry.github.io/2021-02-16-R-plotting-online/



Set up instructions for participants of the workshop:

Thank you for registering for the R Plotting workshop coming up on Tuesday and Wednesday this week. This email is relatively long, but it contains important information about the workshop so please make some time to read through it carefully.

The workshop starts at 9:30am each day and will be held on Zoom. You should have received a calendar invite that contained the Zoom link. 

As the entire workshop will be held online, we'd like you to complete a few steps before Tuesday to ensure your environment is set up and ready to go before the start of the workshop.

1. Computer with a browser and Zoom installed

Ensure you have access to a device (Mac, PC) with reasonable internet bandwidth with a modern browser (eg Chrome) installed.

You will need the Zoom client to join the workshop Zoom call. We will be using some of Zoom's functionalities and these have changed in recent versions of Zoom, so please make sure your Zoom is updated to the latest version. Instructions for updating your Zoom can be found here: https://support.zoom.us/hc/en-us/articles/201362233-Upgrade-update-to-the-latest-version.

The workshop is a 'live coding' format event, where the presenter 'codes' in real time and you code on your device at the same time. We will make use of Zoom, RStudio and a Google Document throughout the workshop. Having multiple screens or joining the zoom call from multiple devices (e.g. your desktop computer + your laptop/tablet), can make it much easier to keep everything visible and organised. More information about setting up your workspace can be found here: https://mq-software-carpentry.github.io/2021-02-16-R-plotting-online/.


2. Install R, RStudio and the tidyverse

Please make sure you have R and RStudio installed on your computer - installation instructions for Windows and macOS operating systems here: https://datacarpentry.org/socialsci-workshop/setup-r-workshop.html (scroll down to find R and RStudio). 

Please make sure you have the tidyverse set of packages installed. To install the tidyverse:
- open RStudio
- in the console run this code: install.packages("tidyverse") 
- if you get asked about installing packages from sources, type ‘no’ and press enter
- after the prompt returns to a ‘>’ symbol run this code: library(tidyverse) 

You may see a message about conflicts, this is a normal message when loading the tidyverse (example of a normal conflict message can be found here: https://tidyverse.tidyverse.org/).

To test that the tidyverse is installed and working properly, please run this small piece of code in the console:

relig_income %>%
  pivot_longer(!religion, names_to = "income", values_to = "count") %>%
  ggplot(mapping = aes(x = income, y = count)) +
  geom_point()

If everything is working correctly you should see a scatter plot in the bottom right corner of RStudio (see the image on page 5 of the workshop shared Google Doc to confirm). Once you have completed the installation and testing of your software go to the shared Google Doc and add your information to the Participants table on page 6.

The time allowed for the workshop is tight, so it is important that your software is working before the start of the workshop. If you need support for installation or making sure R, RStudio, and the tidyverse are working before the workshop there will be an optional drop in Zoom session 1-2 pm on Monday 15 February (Zoom link removed).


3. Complete the pre-workshop survey here (survey link removed). We use this information to calibrate the pace of the workshop and, together with a post-workshop survey, to assess how it went. 

Please read The Carpentries Code of Conduct so we all are aware of how to treat each other respectfully. 

If you have any questions or issues - please don't hesitate to contact us. And if you won't be able to attend, please let us know so we can offer your seat to someone on the waitlist.

