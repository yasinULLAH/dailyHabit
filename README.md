# Daily Habit Tracker

A comprehensive daily habit tracker built with HTML, CSS, and JavaScript. This application allows you to add, edit, and delete multiple habits, mark them as completed each day using a date picker, view your progress over time, and export your habit data to a CSV file. All data is stored locally using `localStorage`, ensuring privacy and persistence between sessions.

## Features

- **Habit Management (CRUD):**
  - **Create:** Add new habits with a name and description.
  - **Read:** View a list of all your habits.
  - **Update:** Edit existing habit information.
  - **Delete:** Remove habits from your list.

- **Daily Habit Tracking:**
  - Select a date using the date picker.
  - Mark habits as completed or not completed for the selected date.
  - Tracking data is stored per date.

- **Progress Overview:**
  - View your completion rate for each habit.
  - Visual progress bars represent your habit consistency over time.

- **Export to Excel-Compatible CSV:**
  - Export all habit tracking data to a CSV file.
  - The CSV includes date, habit name, and completion status.

- **Local Data Storage:**
  - All data is stored in `localStorage`, ensuring persistence between sessions.

- **Single File Application:**
  - The entire application is contained within one HTML file for simplicity and ease of use.

## How to Use

1. **Download the Project:**
   - Clone the repository or download the `index.html` file.

2. **Open the Application:**
   - Open the `index.html` file in a modern web browser (Chrome, Firefox, etc.).

3. **Add Habits:**
   - Click the **"Add Habit"** button to open the habit form.
   - Enter the habit name and an optional description.
   - Click **"Save"** to add the habit to your list.

4. **Edit or Delete Habits:**
   - In the **Habits** table, use the **"Edit"** button to modify a habit's information.
   - Use the **"Delete"** button to remove a habit from your list.

5. **Track Habits Daily:**
   - Select a date using the **"Select Date"** date picker. It defaults to today's date.
   - The **Track Habits** table will display all your habits.
   - Use the checkboxes to mark each habit as completed or not completed for the selected date.
   - Changes are saved automatically in `localStorage`.

6. **View Progress Overview:**
   - The **Progress Overview** section shows your completion rate for each habit.
   - Progress bars visually represent the percentage of days the habit was completed.

7. **Export Data to Excel (CSV):**
   - Click the **"Export Habits to CSV"** button to download your habit tracking data.
   - The file `habit_tracking.csv` will be downloaded, which can be opened in Excel or any spreadsheet application.

8. **Data Persistence:**
   - All data is stored in your browser's `localStorage`.
   - Your data will remain intact even after refreshing or closing the browser, as long as you use the same browser on the same device.

## Technologies Used

- **HTML5:** Structure of the application.
- **CSS3:** Styling and layout.
- **JavaScript:** Functionality and interactivity.
- **LocalStorage:** Data persistence in the browser.
- **CSV Export:** Exporting data to a CSV file for Excel compatibility.

## Customization

- **Styling:**
  - Modify the CSS within the `<style>` tags to change fonts, colors, layout, and overall appearance.

- **Additional Fields:**
  - To add more fields to the habit data (e.g., category, priority), update the habit form, data structure, and rendering functions accordingly.

- **Validation:**
  - Currently, basic validation checks for empty habit names.
  - Enhance validation as needed (e.g., unique habit names, input format checks).

- **Enhanced Features:**
  - Add functionalities such as reminders, notifications, or integration with calendars for a more robust habit-tracking experience.

## Limitations

- **Browser Compatibility:**
  - Use a modern browser that supports `localStorage` and the standard HTML5 APIs for the best experience.

- **Data Portability:**
  - Since data is stored locally, it doesn't sync across devices or browsers.
  - To transfer data, export the CSV and import it into another instance manually.

- **Privacy Note:**
  - Data is stored unencrypted in the browser's `localStorage`.
  - Be cautious when using the application on shared or public computers.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- Inspired by the need for a simple and effective habit-tracking tool.
- Built using vanilla JavaScript without any external libraries for simplicity and ease of understanding.

---

**Enjoy tracking your habits! Feel free to modify the code to suit your specific needs and to add any additional features that enhance your habit-tracking experience.**
