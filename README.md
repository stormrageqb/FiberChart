# FiberChart

## Link

Check it out here: https://fiber-chart.vercel.app/
## Description

This is a mobile-responsive fiber charting application I made for a friend to help him more easily find and connect fibers for his job. I developed this application using HTML, CSS, and JavaScript.

<br>

## Demo

Watch a short demo [here](https://drive.google.com/file/d/1jOfa04vj0hMdUnDaJh-wy_UJeBNZQStr/view)

<br>

## Screenshots

![Screenshot of light-mode with title and grid](./img/screenshots/Light-mode-and-title.png)

<br>
<br>

![Screenshot of dark-mode with grid and form ](./img/screenshots/Dark-mode-grid-and-form.png)

## Functionality

The application can be used to help field service fiber technicians (OSP technician) link the correct fibers out in the field. The number and color system sometimes becomes complex leading to more time spent trying to select and map the correct fibers instead of time spent linking the fibers themselves and getting the job done. That's where this application comes in.

Upon loading the application, users are presented with a grid with numbers and colors that should be familiar to most OSP technicians. The colors correspond to each individual fiber and are standarized based on the fiber optic internet conventions. The numbers are similarly standarized. Users can choose the fiber count they are working with and input a specific number of fibers to chart their fiber pattern. Doing so allows easier access to specific fibers based on their color and number.

It was necessary for this application to be mobile responsive, since most OSPs will utilize the chart out in the field without the convenience of a desktop. The UI will also scale on different desktop sizes. Although it is possible to use the application on a mobile device in portrait orientation, it is recommended to use the landscape orientation on a mobile device instead.

## Real-world Example:

An OSP is stringing up fiber at a fiber pedastal in a suburban residential area. They see they will use a 96-count fiber and that they will need fiber number 72. First, the 96-count fiber number corresponds to the fiber count select box the OSP can select from in the application. Selecting 96 filters all fibers greater than the 96 count, making it easier to find the range of fibers needed. Depending on which fiber the OSP needs, they can input any starting number in the "Input number" box to propagate the fibers they need. In this example, the OSP needs the 96-count fiber starting at fiber number 65. After inputting 65 in the input number box, the grid cell for fiber number 1 will be replaced with 65 and continue counting until it reaches the 96-count fiber mark. This means the end fiber count will be 160 fibers. From this chart the OSP can easily pinpoint the specific fiber they needed at the start, fiber number 72, based on its standardized color and link it to their corresponding fiber cable using a fusion splicer without spending any time counting the fibers themselves to locate fiber number 72. Finished with the job, the OSP taps the reset button, ready for the next task.

<br>

## Bonus Feature

1. Users will sometimes find themselves connecting fiber in dark places. I felt it would be beneficial to add a dark-mode feature to increase the ease of use and comfort in those situations. The default mode is light-mode. Users can enable dark-mode by clicking the moon icon located near the top right of the page. It is then possible to switch back to light-mode by clicking the sun icon. The transitions between either mode are smooth and the selected mode is saved to local storage, so that the current mode will persist even after refreshing the page or using the reset button.

## Technology

HTML
<br>
CSS
<br>
JavaScript
<br>

