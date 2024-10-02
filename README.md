
# React Ticket Management System

This is a simple ticket management system built with **React**. It allows users to view and manage tickets, sort them based on user, and display user-specific icons. The project is designed for task and ticket management, especially in environments where grouping and ordering by user or priority is essential.

## Features

- **User-based ticket sorting**: Group tickets by users and display user avatars.
- **Dynamic tag system**: Each ticket has dynamic tags based on its priority.
- **Responsive design**: Adapts to different screen sizes.
  
## Project Structure

- `App.js`: Main entry point of the app.
- `TicketCard.js`: Displays individual tickets, including user icons and tags.
- `KanbanBoard.js`: Renders a list of users or tickets.
- `Card.css`: Styling for the ticket cards and profile icons.


## Usage

- Run the application and start sorting tickets based on users or priorities.
- Customize the `userList` and `ticketDetails` in the `App.js` file to fit your data.

## Components

1. **App.js**
   - Handles the main logic of grouping and rendering lists of tickets.
   
2. **TicketCard.js**
   - Displays individual ticket details, user avatars, and priority tags.
   
3. **KanbanBoard.js**
   - Handles rendering grouped lists, allowing for sorting by user or other attributes.

## Customization

- **Icons**: Modify user avatars by adding a `profileImage` property to each user in `userList`.
- **Tags**: Each ticket displays a dynamic icon depending on its priority level, which can be updated in `TicketCard.js`.


