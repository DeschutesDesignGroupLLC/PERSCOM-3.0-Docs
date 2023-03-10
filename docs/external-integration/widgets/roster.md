# Roster Widget

The roster widget outputs a table-based list of your personnel, similar to the roster within your Dashboard.

## Code Snippet

<!-- prettier-ignore -->
::: info 
Make sure to replace APIKEY and PERSCOMID with the appropriate values. 
:::

```html
<!-- Place the code block where you would like the widget displayed on your website. !-->
<!-- Replace APIKEY and PERSCOMID with your API key and PERSCOM Account ID, respectively. !-->

<div id="perscom_widget_wrapper">
  <script
    id="perscom_widget"
    data-perscomid="PERSCOMID"
    data-apikey="APIKEY"
    data-widget="roster"
    src="https://widget.perscom.io/widget.js"
    type="text/javascript"
  ></script>
</div>
```

## Examples

The following is an example of the Roster Widget being displayed within the PERSCOM Dashboard.

![Widget Roster Preview](https://assets.perscom.io/images/widget-roster-preview.png)

![Widget Roster User Preview](https://assets.perscom.io/images/widget-roster-user-preview.png)

## Scopes

The following scopes will need to be added to your API key to properly display the data.

- `view:assignmentrecord` Can view an assignment record.
- `view:awardrecord` Can view an award record.
- `view:combatrecord` Can view a combat record.
- `view:qualificationrecord` Can view a qualification record.
- `view:rankrecord` Can view a rank record.
- `view:servicerecord` Can view a service record.
- `view:unit` Can view a unit.
- `view:user` Can view a user.
