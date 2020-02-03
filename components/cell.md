# Cell

Cells are interactive list items. They contain pieces of information related to a single item in a group.

## Usage

Use cells to display items that have a main action associated with them. The action will most of the time be a navigation to a new view.

## Interaction

The whole cell should be clickable or tappable when the main action navigates to a new view. On iOS, it's recommended to show a chevron pointing right to emphasize the navigation hierarchy.

The main action may also be a toggle (checkbox or radio), in which case tapping the whole cell shouldn't do anything, only the toggle element should trigger the action.

## Anatomy

### Typography

We use distinct text styles to associate groups of information together. The styles should be based on the hierarchy of information, and their distinction shouldn't be based only on position or colour as these don't convey hierarchy strongly enough.

### Size

The height of the component should be dictated by its content and the paddings on top and bottom. However, we aim for the same minimum height across all cells on each platform to ensure a predictable tap/click area. The minimum height should be the same as the height of the component when it has a single line on each block of text.

### Elements

| Element        | Description                                                                                                                                                                                 | Text Style  | Required |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | -------- |
| Title          | Main piece of text that describes the item.                                                                                                                                                 | Title 4     | ✅       |
| Description    | Secondary piece of text that supports the title.                                                                                                                                            | Paragraph 2 |          |
| Media          | Any image or icon that provides visual support for the item.                                                                                                                                |             |
| Secondary area | It can be used for: <br/> • chevron pointing right to emphasize navigation <br/> • toggling an option (checkbox or radio) <br/> • secondary blocks of text related to Title and Description |             |

## Development documentation

| Platform | Status                                                                                                                                                                                                                                                                            |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android  | Planned                                                                                                                                                                                                                                                                           |
| iOS      | Planned                                                                                                                                                                                                                                                                           |
| Web      | [Navigation Option](https://transferwise.github.io/neptune-web/components/NavigationOption) <br/> [Checkbox Option](https://transferwise.github.io/neptune-web/components/CheckboxOption) <br/> [Radio Option](https://transferwise.github.io/neptune-web/components/RadioOption) |
