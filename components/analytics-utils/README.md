# Analytics-utils - Base Component

>**Note:**  
>This is a base component for product add to cart functionality.
>It won't have any output on the user interface. It only initializes core functions. 

You will find the necessary resources for this component available here:
[resources](/components/analytics-utils/resources). Please add these with the
method appropriate to your chosen framework. 

[Base file](/components/analytics-utils/resources/assets/js/klevu-analytics-utils.js) contains the core logic of the functionality.

Below code snippet is to show, how to initialize and use base component into the relevant scope.

```javascript
/** Initalize base component to the scope*/
klevu.analyticsUtils(TARGET_SCOPE);

/** Usage of base component functions */
TARGET_SCOPE.analyticsUtils.base.FUNCTION_NAME();
```

Try accessing analyticsUtils base component.