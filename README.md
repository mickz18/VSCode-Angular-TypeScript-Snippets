[![Version](https://vsmarketplacebadge.apphb.com/version/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

# VSCode Angular TypeScript & Html Snippets
Visual Studio Code TypeScript and Html snippets and code examples for Angular 2+

# Important
This extension is optimized for devlopers that use Angular 2+ and are no longer using Angular 1.
If you type in Angular 1 keywords, it will suggest an Angular 2 solutions. 
This is by design and ment to help developers learn how Angular 1 concepts and techniques map to Angular 2+

See example below for ng-repeat and ng-click:

![ngRepeatSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngRepeatSnippet.gif)


All code snippets are based on and follow the Angular style guide https://angular.io/docs/ts/latest/guide/style-guide.html and can be 

# Usage

All Angular snippets starts with "ng-".
Multiple snippets come in multiple variations. For instance when you want to create a new component you can choose between having the template and css inline or not:
* ng-component
* ng-component-inline


### ng-component

![ngComponentSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngComponentSnippet.gif)

### ng-for

ng-for currently has even more variations, so make sure you pick the one you want before you press enter:
* ng-for
* ng-for-index
* ng-for-li
* ng-for-trackBy

![ngForSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngForSnippet.gif)

### Angular Material
All Material snippets starts with "m-" and there are now over 30 Material snippets in this package.

# Pro Tip

You don't need to type any dashes: "ngrxr" -> "ng-rx-reducer" snippet


### TypeScript & Html Snippets

| Snippet | Description |
| ------- | ----------|
| m-button | Rectangular Material button w/ no elevation. |
| m-button-fab | Circular button w/ elevation. |
| m-button-fab-mini | Small circular button w/ elevation. |
| m-button-icon | Circular Material button with a transparent background |
| m-button-raised | Rectangular Material button w/ elevation. |
| m-button-toggle | Material toggle button |
| m-card | Material Basic Card |
| m-checkbox | Material Checkbox |
| m-chip | Material Chip |
| m-chip-list | Material Chip List |
| m-chip-list-stacked | Material Chip Stacked List |
| m-datepicker | Material Datepicker |
| m-expansion-panel | Material Expansion Panel |
| m-grid-list | Material Grid List |
| m-icon-fontawesome | Material Font Awesome Icon |
| m-icon-svg | Material SVG Icon |
| m-input | Material Input Textbox |
| m-list | Material List |
| m-list-item | Material List Item |
| m-list-ngfor | Material List ngFor |
| m-paginator | Material Paginator |
| m-radiobutton | Material Radio Button |
| m-radiobutton-option | Material Radio Button Option |
| m-select | Material Select |
| m-slide-toggle | Material Slide toggle |
| m-slider | Material Slider |
| m-slider-thumbLabel | Material Slider thumbLabel |
| m-slider-tickInterval | Material Slider tickInterval |
| m-slider-tickInterval-auto | Material Slider tickInterval Auto |
| m-slider-vertical | Material Vertical Slider |
| m-spinner | Material Determinate Spinner |
| m-spinner-indeterminate | Material Indeterminate Spinner |
| m-stepper-vertical | Material Vertical Stepper |
| m-tab | Material Tab |
| m-tab-group | Material Tab Group |
| m-table | Material Table |
| m-table-column | Material Table Column |
| m-toolbar | Material toolbar |
| m-toolbar-multiRow | Material Toolbar with multiple rows |
| m-toolbar-row | Material toolbar row |
| m-tooltip | Material Tooltip |
| m-tooltip-position | Material Tooltip position |
| m-tooltip-with-position | Material Tooltip with position |
| ng-afterContentChecked | Lifecycle hook: Called after every check of the component's or directive's content |
| ng-afterContentInit | Lifecycle hook: Called after ngOnInit when the component's or directive's content has been initialized |
| ng-afterViewChecked | Lifecycle hook: Called after every check of the component's view. Applies to components only |
| ng-afterViewInit | Lifecycle hook: Called after ngAfterContentInit when the component's view has been initialized |
| ng-binding-oneway | Property: [property]=\"expression\" |
| ng-binding-twoway | Two-way data binding with the NgModel |
| ng-bootstraping | Bootstraping example |
| ng-button | A button element with a click event |
| ng-button-submit | A submit button element with a click event |
| ng-class | CSS class |
| ng-click | Click event |
| ng-component | Component with template and style urls |
| ng-component-inline | Component with inline Template and Styles |
| ng-component-value-accessor | Angular Component With NG_VALUE_ACCESSOR |
| ng-conf | The World's Original Angular Conference |
| ng-controller | Use component instead. |
| ng-debug | pre obj pipe json |
| ng-debug-async | pre obj pipe async pipe json |
| ng-directive | Directive template |
| ng-directive-attribute | Attribute directive |
| ng-directive-css | CSS directive |
| ng-doCheck | Lifecycle hook: Called every time that the input properties of a component or a directive are checked |
| ng-event | Event: (event) = \"onEvent()\" |
| ng-filter | For performance reasons, no comparable pipe exists in Angular 2. Do all your filtering in the component. If you need the same filtering code in several templates, consider building a custom pipe. |
| ng-for | For-loop directive |
| ng-for-index | For-loop directive with index |
| ng-for-li | For-loop directive with li element |
| ng-for-trackBy | For-loop directive with trackBy |
| ng-fx-col | Flex Layout Column |
| ng-fx-col-reverse | Flex Layout Reverse Column |
| ng-fx-import | Flex Layout Import |
| ng-fx-item | Flex Layout Item |
| ng-fx-item-align | Flex Layout Item with fxFlexAlign |
| ng-fx-item-fill | Flex Layout Item with fxFlexFill |
| ng-fx-item-offset | Flex Layout Item with fxFlexOffset |
| ng-fx-item-order | Flex Layout Item with fxFlexOrder |
| ng-fx-layout | Flex Layout Property |
| ng-fx-layout-align | Flex Layout Align Property |
| ng-fx-layout-gap | Flex Layout Gap Property |
| ng-fx-row | Flex Layout Row |
| ng-fx-row-reverse | Flex Layout Reverse Row |
| ng-hide | Usage: Bind to the hidden property. |
| ng-href | Usage: Bind to the href property. |
| ng-http-get | Http observable get request |
| ng-http-get-post | Http observable get & post request |
| ng-httpClient-get | HttpClient observable get request |
| ng-if | If directive: *ngIf=\"expression\" |
| ng-if-else | v4: If else directive: *ngIf=\"expression; else\" |
| ng-if-then-else | v4: If then else directive: *ngIf=\"expression; then; else\" |
| ng-import | import module or component from path; |
| ng-input | Class Input Property |
| ng-interpolation | Interpolation: {{ interpolation }} |
| ng-module | Feature Module |
| ng-module-root | App root module |
| ng-ngOnChanges | Lifecycle hook: Called before any other lifecycle hook |
| ng-onDestroy | Lifecycle hook: Called before the instance is destroyed |
| ng-onInit | Lifecycle hook: Called after the constructor |
| ng-orderBy | For performance reasons, no comparable pipe exists in Angular 2. Instead, use component code to order or sort results. If you need the same ordering or sorting code in several templates, consider building a custom pipe. |
| ng-output | Class Output Event |
| ng-pipe | Pipe template |
| ng-pipe-async | Async pipe - Usage: observable_or_promise_expression &#x7c; async |
| ng-pipe-currency | Currency pipe - Usage: money &#x7c; currency:'EUR' |
| ng-pipe-date | Date pipe - Default format: 09/15/1971 |
| ng-pipe-date-custom | Date pipe - Format: \"MM/dd/yy\" = 09/15/71 |
| ng-pipe-date-full | Full date pipe - Format: Wednesday, September 15, 1971 |
| ng-pipe-date-short | Short date pipe - Format: 09/15/1971 |
| ng-pipe-decimal | Decimal pipe - Usage: number_expression &#x7c; decimal[:digitInfo] |
| ng-pipe-example | Angular pipe example |
| ng-pipe-json | Json pipe - Usage: object &#x7c; json |
| ng-pipe-lowercase | Lowercase pipe |
| ng-pipe-percent | Percent pipe - Usage: number_expression &#x7c; percent[:digitInfo] |
| ng-pipe-slice | Slice pipe - Usage: array_or_string_expression &#x7c; slice:start[:end] |
| ng-pipe-titlecase | v4: Titlecase pipe |
| ng-pipe-uppercase | Uppercase pipe |
| ng-property | Property: [property]=\"expression\" |
| ng-repeat | Use ngFor instead. |
| ng-route-guard-canactivate | CanActivate Guard Route |
| ng-route-guard-canactivatechild | CanActivateChild Route |
| ng-route-guard-candeactivate | CanDeactivate Guard Route |
| ng-route-guard-canload | CanLoad Guard Route |
| ng-route-guard-resolve | Resolve Guard Route |
| ng-router | Router template |
| ng-router-appmodule | Routes to include in root module |
| ng-router-attribute | Router link |
| ng-router-featuremodule | Routes to include in a feature module |
| ng-router-link | Router link |
| ng-router-linkActive | Router active link |
| ng-router-outlet | Router outlet element |
| ng-router-outlet-name | Router outlet element with name |
| ng-rx-action | ngRx Single action |
| ng-rx-actions | ngRx Actions class |
| ng-rx-module | ngRx Root Module |
| ng-rx-reducer | ngRx Reducer |
| ng-rx-util | ngRx Util |
| ng-service | Basic service |
| ng-show | Usage: Bind to the hidden property. |
| ng-src | Usage: Bind to the src property. |
| ng-style | CSS style |
| ng-switch | Switch template |
| ng-test-component-async | TODO |
| ng-test-component-synchronous | TODO |
| ng-test-directive | TODO |
| ng-test-pipe | Test a pipe |
| ng-test-service | TODO |
| ng-validator | Angular validator snippet |
| rx-import-add-observable | RxJS Import Observable |
| rx-import-add-operator | RxJS Import Add Operator |
| rx-import-all | RxJS import the entire core set of functionality |
| rx-import-observable | RxJS Import Observable |
| wat | A lightning talk by Gary Bernhardt from CodeMash 2012. ng-wat talk by Shai Reznik in 2015 |


## Installation (Mac)

1. Launch VS Code 
2. Quick Open (⌘+P)
3. Enter the following command and press enter: 'ext install Angular-BeastCode'
4. Choose extension (Author: Mikael Morlund)
5. Reload VS Code 


## Installation (Windows, Linux)

1. Launch VS Code 
2. Quick Open (Ctrl-Shift-P)
3. Enter the following command and press enter: 'ext install Angular-BeastCode'
4. Choose extension (Author: Mikael Morlund)
5. Reload VS Code 


## Feedback

Please send any feedback or suggestions to @Mike_BeastCode (Twitter) or create an issue on GitHub.

## Open Source

This is an open source project and if you want to contribute I've added issues on github that are easy to start with. [![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/labels/first-timers-only)


## Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data.


## License

MIT