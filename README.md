# Ionic 4 - Tab Bar

i followed the tutorial of Simmon Grimm: [How to Add A Tab Bar to Your Ionic 4 App](https://youtu.be/_BnCRIZ1nDk)

![alt text](https://github.com/martha-softwaredeveloper/Ionic4-TabBar/blob/master/src/assets/ionic4-tab-bar_screenshot.png)

## App Configuration

Create ionic project with tabs and pages
1. ionic start AppName blank --type=angular
2. ionic g page pages/tabs
3. ionic g page pages/tab1
4. ionic g page pages/tab2
5. ionic g page pages/details

## Routing

1. At app-routing.module.ts, set tabs as main path --> code lines: 5
2. At tabs.module.ts, set routes (tabs as path and its children) --> code lines: 10 - 25
 

## Tabs

1. At tabs.page.html, create the bottom tab bar with ion-tabs --> code lines: 1 - 15
2. Test tab with console message
3. At tabs.page.html, add click attribute --> code lines: 9
4. At tabs.page.ts, add function --> code lines: 15 - 17
 

## Details

1. At app-routing.module.ts, add details as a path --> code lines: 6
2. At tabs.module.ts, add details as a path --> code lines: 17
3. At details.page.html, add back button --> code lines: 3 - 5
4. At tab1.page.html, add 2 buttons --> code lines: 7 - 10
5. At tab1.page.ts, add function
6. Add private router: Router as param in constructor --> code lines: 11
7. Add function --> code lines: 16 - 18

## Author

Simmon Grimm


## License

This project is licensed under the MIT License.

