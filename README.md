![N|Solid](https://www.mealsuite.com/a/img/mealsuite-logo.png)

# Backend Developer Assignment

### Simple Photo Gallery Application


You are requested to create a simple Photo Gallery web application to manage your photos. The app is intented to use internally to handle collection of your private photos. There will be no need for any user registration or user authentication. The app should use:

    Ruby 2.7.x version
    Rails 5.2.x version 
    Postgres or MySQL database 

### Funtionalities:

**Gallery:** Allow user to manage Gallery

- A simple form to allow the user to create Gallery with name and a short description
- Gallery name will be unique within your app.
- Gallery name and short description are required
- CRUD functions that allow you to list, view, edit and delete your gallery

**Photo:** Allow user to upload and manage photo

- A simple form to allow the user to create photo with name, shooting date and a short description

- The form should allow the user to upload the photo with above information

- Photo name will be unique within your app.

- Photo and photo name are required

- Shooting date and description are optional

- Photo should be stored in local folder

- CRUD functions that allow you to list, view, edit and delete your photo

- If the user chooses to delete a gallery with an existing photo, the app should ask for confirmation and delete all photos stored in the gallery if the user confirms

  and delete all photos stored in the gallery if the user confirms

**Pagination:**
- Gallery and photo should be paginated by 10 items per pages
- Users will be able to navigate via different pages.

**Comment:**

- A simple comment form under your photo to allow users to create comment
- The required fields will be user’s name and comment
- The comments are to be added under the photo with content, username and created_date
- Comments are deleted if Photo is deleted

**Sorting:**

- User will be able to sort your gallery and photo by name, shooting date, created_date in ascending and descending orders

**Searching:**

- A simple form to allow the user to enter search term and a Search button

- Application will search gallery and photo by name

- Search results are displayed in a listing page with pagination

**Tag:**

- CRUD function to allow the user list, create, view, edit and delete your tag

- User will be able to add/remove tag from photo or gallery

- Associated tags are displayed in photo and gallery detail page

- If the user clicks on a tag, it will go to a page that lists all photos and galleries with the same tag

### UI:
- The application should have a simple UI
- You are encouraged to use available gems and libraries such as Bootstrap
- You also can use your own simple styling if  prefer
- Please do not spend too much time on styling

### Gems:
- You are encouraged to use available gems to assist your coding.
### Unit Test:

- You will need to implement unit tests for methods on your models, controllers and helpers if any

- You are required to use Rspec for writing your unit test case.

- Your unit tests should not fail when running

- A service will be run to measure your test coverage. Your test coverage should be >= 50% of your overall coding.

### Code Styling:
- Please pay attention to your code styling and follow common ruby and rails best practices
- Measurement tools will be run to measure your code cleanness and quality

### Performance:
- Performance is not an assessment for this assignment. Please focus on your logic
- However optimizing code and database queries will be a plus

### Submission:
- Please host your solution publicly on github, gitlab or bitbucket and send us the link.
- Please also incldue total time that you spend to finish the assignment
