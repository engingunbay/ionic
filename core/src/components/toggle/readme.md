# ion-toggle

Toggles change the state of a single option. Toggles can be switched on or off by pressing or swiping them. They can also be checked programmatically by setting the `checked` property.



<!-- Auto Generated Below -->


## Properties

| Property   | Attribute  | Description                                                                                                                                                                                                                                                            | Type                          | Default        |
| ---------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | -------------- |
| `checked`  | `checked`  | If `true`, the toggle is selected.                                                                                                                                                                                                                                     | `boolean`                     | `false`        |
| `color`    | `color`    | The color to use from your application's color palette. Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`. For more information on colors, see [theming](/docs/theming/basics). | `string \| undefined`         | `undefined`    |
| `disabled` | `disabled` | If `true`, the user cannot interact with the toggle.                                                                                                                                                                                                                   | `boolean`                     | `false`        |
| `mode`     | `mode`     | The mode determines which platform styles to use.                                                                                                                                                                                                                      | `"ios" \| "md"`               | `undefined`    |
| `name`     | `name`     | The name of the control, which is submitted with the form data.                                                                                                                                                                                                        | `string`                      | `this.inputId` |
| `value`    | `value`    | The value of the toggle does not mean if it's checked or not, use the `checked` property for that.  The value of a toggle is analogous to the value of a `<input type="checkbox">`, it's only used when the toggle participates in a native `<form>`.                  | `null \| string \| undefined` | `'on'`         |


## Events

| Event       | Description                                  | Detail                  |
| ----------- | -------------------------------------------- | ----------------------- |
| `ionBlur`   | Emitted when the toggle loses focus.         | void                    |
| `ionChange` | Emitted when the value property has changed. | CheckedInputChangeEvent |
| `ionFocus`  | Emitted when the toggle has focus.           | void                    |


## CSS Custom Properties

| Name                          | Description                                  |
| ----------------------------- | -------------------------------------------- |
| `--background`                | Background of the toggle                     |
| `--background-checked`        | Background of the toggle when checked        |
| `--handle-background`         | Background of the toggle handle              |
| `--handle-background-checked` | Background of the toggle handle when checked |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
