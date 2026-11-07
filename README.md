# 🦷 SmileCare

**SmileCare** is a lightweight, responsive dental-care habit tracker
built with HTML, CSS, and vanilla JavaScript. It helps users build
consistent oral-care routines with a brushing timer, daily habit
checklist, progress tracking, and useful reminders.

## Features

-   **2-minute brushing timer** with four 30-second brushing zones.
-   **Daily habit checklist** for morning brushing, night brushing,
    flossing, and mouthwash.
-   **Custom habits** that users can add or remove.
-   **Brushing streak** based on completing both morning and night
    brushing.
-   **Weekly progress** for brushing and flossing, including a
    previous-week flossing count.
-   **Toothbrush replacement reminder** based on a 3-month (90-day)
    interval.
-   **Dentist appointment countdown** showing the days until the next
    appointment.
-   **Tooth-friendly food guide** with foods to choose and foods to
    limit.
-   **Daily oral-care tip** selected from a set of tips.
-   **Three languages:** English, French, and Arabic, with right-to-left
    layout for Arabic.
-   **Light and dark appearance:** follows the device color-scheme
    preference, with dark mode support.
-   **Local data storage:** saves habits, progress, language, and dates
    in the browser using `localStorage`.

## Built With

-   **HTML5** --- page structure
-   **CSS3** --- responsive layout, styling, and theme variables
-   **JavaScript** --- timer, habit tracking, reminders, language
    switching, and local persistence
-   **Browser Local Storage** --- saves data on the user's device

## Getting Started

SmileCare is a front-end project and does not require a package
installation or database.

### Run locally

1.  Download or clone this repository.
2.  Open the project folder.
3.  Open `index.html` in a modern web browser.

You can also use the **Live Server** extension in Visual Studio Code:

1.  Open the project folder in VS Code.
2.  Right-click `index.html`.
3.  Select **Open with Live Server**.

## Project Structure

``` text
SmileCare/
└── index.html
```

The current version contains the HTML, CSS, and JavaScript in a single
`index.html` file.

## How Data Is Saved

SmileCare stores user data in the browser's `localStorage` under the key
`smilecare-v1`. This means:

-   Data remains available in the same browser on the same device.
-   Data is not automatically synchronized between devices or browsers.
-   Clearing the browser's site data may remove saved SmileCare
    information.
-   There is currently no server or cloud database.

## Important Notes

-   The brushing timer guides a two-minute routine and divides it into
    four 30-second zones.
-   The toothbrush reminder is based on the date entered by the user and
    a 90-day interval.
-   Appointment countdowns use the date selected by the user.
-   SmileCare is an educational habit-tracking tool. It does not
    diagnose dental conditions or replace advice from a dentist.

## Possible Future Improvements

-   Export and import personal progress.
-   Browser notifications for brushing and appointments.
-   Optional cloud backup and account synchronization.
-   More languages and customizable reminders.
-   Separate HTML, CSS, and JavaScript files as the project grows.

## Author

**Mohammed Maghraoui**

-   GitHub: [MohammedMaghraoui](https://github.com/MohammedMaghraoui)
-   LinkedIn: [Mohammed
    Maghraoui](https://www.linkedin.com/in/mohammed-maghraoui/)

## License

Add a license file if you intend to distribute this project under a
specific open-source license.
