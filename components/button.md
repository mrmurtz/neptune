# Button

Buttons allow users to take an action whether it's a tap or a click.

## Usage

There are different types of buttons to allow the user to scan for the most important actions.

#### Placement

| Type            | Description                                                                                            |
|-----------------|--------------------------------------------------------------------------------------------------------|
| Button          | Standard button used inline with the content.                                                          |
| Footer button   | Single button per screen at the bottom. Sits outside the scroll container, always visible to the user. |
| Circular button | Actions related to the object it is in or nearby to. Actions may change state or start flow.           |

#### Hierarchy

| Type      | Description                                                                                                                          | Standard | Footer | Circular |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------|----------|--------|----------|
| Primary   | The main action on a screen - avoid using more than one per screen.                                                                  | 🖼️        | 🖼️      | 🖼️        |
| Secondary | The possible secondary action(s) on a screen - avoid using more than 3 per screen.                                                   | 🖼️        | 🖼️      | 🖼️        |
| Tertiary  | A possible but unlikely action to be taken on the screen.                                                                            | 🖼️        | 🖼️      | 🖼️        |
| Pay       | Use at the start and end of a payment flow.                                                                                          | 🖼️        | 🖼️      | 🖼️        |
| Destroy   | Use as a non-reversible destructive action.                                                                                          | 🖼️        | 🖼️      | 🖼️        |
| Link      | A button embedded in text or part of a non-interactive component. Use carefully so that the text linked has a large enough tap area. | 🖼️        | X      | X        |

## Development documentation

| Platform | Status                                                       |
|----------|--------------------------------------------------------------|
| Android  | [Available](https://github.com/transferwise/neptune-android) |
| iOS      | Planned                                                      |
| Web      | [Available](https://transferwise.github.io/neptune-web)      |
