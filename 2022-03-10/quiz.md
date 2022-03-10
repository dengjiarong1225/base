style-guide

一：

A: 
``` js
export default {
  name: 'Todo',
  // ...
}
```

B: 
``` js
export default {
  name: 'TodoItem',
  // ...
}
```


二：

A: 
```
components/
|- BaseButton.vue
|- BaseTable.vue
|- BaseIcon.vue
```

B: 
```
components/
|- MyButton.vue
|- VueTable.vue
|- Icon.vue
```

三：

A: 
```
components/
|- SearchButtonClear.vue
|- SearchButtonRun.vue
|- SearchInputExcludeGlob.vue
|- SearchInputQuery.vue
|- SettingsCheckboxLaunchOnStartup.vue
|- SettingsCheckboxTerms.vue
```

B:
```
components/
|- ClearSearchButton.vue
|- ExcludeFromSearchInput.vue
|- LaunchOnStartupCheckbox.vue
|- RunSearchButton.vue
|- SearchInput.vue
|- TermsCheckbox.vue
```

四：

A: 
``` html
<!-- 在 DOM 模板中 -->
<my-component/>
```

B:
``` html
<!-- 在 DOM 模板中 -->
<my-component></my-component>
```