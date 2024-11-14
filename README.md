# 1. Styled Button Component with Hover Effect
## Task: Create a Button component with minimal styling using Styled Components.
## Requirements:
- Style the button with a background color, padding, and a slight hover effect.
- Add a `primary` prop that changes the button’s background color when set to true.

## Example Usage:
```
<Button primary>Primary Button</Button>
<Button>Secondary Button</Button>
```

## Hints
- Keep styling minimal with only basic color and padding.
- For primary color, you can use `#007BFF` (on hover: `#0056b3`) else `#6C757D` (on hover: `#5a6268`)

# 2. Counter Component with State Management

## Task: Create a Counter component that increments and decrements a count value using React state.

## Requirements:
- Use the `useState` hook to manage the count.
- The component should have "Increment" and "Decrement" buttons to update the count.
- Display the current count in the middle.

## Example Usage:
`<Counter />`

## Hints
- Use `setCount` to update the state, and display the count between the two buttons.

# 3. Todo List with State Management
## Task: Create a TodoList component to manage and display a list of tasks.

## Requirements:
- Use the useState hook to manage an array of tasks.
- Add an input field to type in a new task, with an "Add Task" button to submit it.
- Display each task as a list item, and allow users to remove a task by clicking a "Remove" button next to it.

## Example Usage:
```
<TodoList />
```

## Hints:
- Use state to store the task list, and use array methods like `.filter()` to remove tasks.
