### `bm-accordion`

```html
<bm-accordion
   allowMultiple="boolean"          <!-- Need more item to be expanded at the same time ? -->
   collapseAll="boolean">           <!-- Need to collapse all items initially ? -->

 <bm-accordion-item
      variant="string"              <!-- Which style should i be ? 'elevated' or 'outlined' -->
      expanded="boolean"            <!-- Expand me ? -->
      toggleLocked="boolean"        <!-- Disabled me ? -->
      (isExpanded)="isExpan($event:boolean)">     <!-- what to do, when i expand and collapse ? -->
   
    <span startContent>Iam a title</span>
       Iam a description
  </bm-accordion-item>

  <!-- ... and another bm-accordion-items as you need  -->
</bm-accordion>
```
---

### `bm-avatar`

```html
<bm-avatar
  class=""
  size="string" <!-- xs | sm | md -->
  color="string" <!-- secondary | primary -->

  <!-- Avatar styles: pick only one -->
  label="Akram Asharf" <!-- appears : AA -->
  icon="string" <!-- ex; bm-maskImage-global_person-->
  imageSrc="string" <!-- ex; assets/person -->

></bm-avatar>
```

---

### `bm-datepicker`

```html
<bm-datepicker
  class="..."  <!-- Need more classes? ex; 'bm-w-[330px]' -->
  lang="string"  <!-- Which lang ? ex; 'en', 'ar' -->
  isRange=boolean  <!-- Determines if the datepicker is for a single date or a date range. true for range, false for single date -->
  [(ngModel)]="['12/03/2023', '14/04/2023']"  <!-- Two-way data binding for the selected date or date range -->
  [inputPlaceholder]="'Select date range'"  <!-- Placeholder text for the input field -->
  [minDate]="'15/02/2023'"  <!-- The minimum date that can be selected. Date format should be dd/MM/yyyy -->
  [maxDate]="'14/05/2023'"  <!-- The maximum date that can be selected. Date format should be dd/MM/yyyy -->
  [disabled]="false"  <!-- Disables the datepicker if set to true -->
  [startMinMaxConfig]="{ minStart: '15/05/2024', maxEnd: '28/05/2024' }"  <!-- Configuration for start date restrictions in range selection -->
  [endMinMaxConfig]="{ maxEnd: '10/07/2024' }"  <!-- Configuration for end date restrictions in range selection -->

></bm-datepicker>
```


### `bm-badge`

```html
  <bm-badge data="9" badgeSize= "xxs | xs | sm | lg" badgeType= "standard | assistive" ></bm-badge>
```



### `bm-breadcrumb`

```html
```


