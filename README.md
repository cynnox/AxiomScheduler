# Axiom Scheduler


### Usage

User `ax-scheduler` tag to user scheduler.

```html

<ax-scheduler [axEventTemplate]="eventTemplate" [axSchedulerView]="'week'"
      [axEventToolbar]="true" [axAnimation]="'default" [axTheme]="'light'" [axEvents]="events"
      [axDragStep]="5" [axShowLocale]="true">
</ax-scheduler>

```

### @Input() Params

| Name | Type | Default | Usage |
| ------ | ------ | ------ | ------ |
| axEvents | -- | AxiomSchedulerEvent [ ] | List of scheduler events |
| axStartDate | Date | Today | Current date of scheduler  |
| axEventTemplate | TempateRef | -- | Custom template for events  |
| axDragStep | Number | 5 | Events drag and resize step  |
| axLocale | String | 'en' | Set scheduler locale, for more information of available locales, check [Momentjs i18n document](https://momentjs.com/docs/#/i18n/)  |
| axEventToolbar | boolean | false | Show/Hide events toolbar  |
| axSchedulerView | AxiomSchedulerView | 'day' | Set default scheduler view, Available views : 'day', 'week', 'month', 'year'  |
| axViews | AxiomSchedulerView [ ] | All views | Set scheduler available views to show  |
| axTheme | AxiomSchedulerTheme | 'light' | Set default scheduler theme, Available themes : 'light', 'dark'  |
| axAnimation | AxiomSchedulerAnimation | 'default' | Set default scheduler animation effects, Available animations : 'animation1', 'animation2', 'animation3', 'animation4', 'default', 'none'  |
| axShowLocale | boolean | true | Show/Hide locale dropdown  |
| axShowLocale | boolean | true | Show/Hide locale dropdown  |
