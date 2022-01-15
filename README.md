# Integration-Demo
_A demo project on data visualization using Google's Big-Query, Data-Studio and sites_

### Requirements
* Valid Google account with active logins in:
  - Big Query
  - Data Studio
  - Google site
* Browser - Chrome / Firefox

### Resources
* GCP platform login - https://cloud.google.com/?authuser=1
* Google data-studio login - https://datastudio.google.com/

### Demo project
- Below is the overall architecture design adopted for this project
![alt text](https://github.com/KurianUthuppu/Integration-Demo/blob/a9e4ecb0c1d5d2caa7690578dcb5d0b615e88dbf/Design_Architecture.jpg)
- Connect IoT data or data from other servers or schedule data uploads to Big-Query
- Schedule queries on the requisite datatables
- Create data-studio dashboards using 'Export with data-studio' option from Big-Query or Big-Query connector in data-studio
- Click embed report in the share button and copy the embed code
- Create a google site for the dashboards using any ready-made template available in google sites
- Designing a web-page or customizing a ready-made template in google site is easy
  - You can insert text, image, shapes, vidoes in the google site easily using the provided options
- Click embed button on the right hand side and paste the earlier copied code from Data-Studio
  - The data-studio dashboard would be loaded in the google site
  - Click the pencil button on the top left corner of the embedded dashboard and make width, height as 100%
    -> This will adjust the dashboard size to the size of the browser window
  - You may further drag the embedded dashboard selection to make it view easily completely in one page without sidebars
- Publish the google site using the publish button on the top-right corner
- Give 'Published Viewer' option to requisite personnel using 'share with others' option
  - In this way, all the dashboards of a particular project can be embedded in a single google site and made available to all requisite personnel
  - Authorized personnel could view the dashboards using desktop/mobile devices and extract data with the selected inputs/date-ranges as well 
- You may go one step further and enable google chat-bot to help authorized users to access requisite data in the Big-Query
  - Detailed steps to the same is given here -> https://github.com/KurianUthuppu/Google_Chatbot.git
