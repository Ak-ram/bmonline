## bm-datepicker

```html
<bm-datepicker
  class="bm-w-[330px]"  <!-- Custom CSS class for styling -->
  [lang]="'en'"  <!-- Language for the datepicker. Accepts 'en' for English or 'ar' for Arabic -->
  [isRange]="true"  <!-- Determines if the datepicker is for a single date or a date range. true for range, false for single date -->
  [(ngModel)]="['12/03/2023', '14/04/2023']"  <!-- Two-way data binding for the selected date or date range -->
  [inputPlaceholder]="'Select date range'"  <!-- Placeholder text for the input field -->
  [minDate]="'15/02/2023'"  <!-- The minimum date that can be selected. Date format should be dd/MM/yyyy -->
  [maxDate]="'14/05/2023'"  <!-- The maximum date that can be selected. Date format should be dd/MM/yyyy -->
  [disabled]="false"  <!-- Disables the datepicker if set to true -->
  [startMinMaxConfig]="{ minStart: '15/05/2024', maxEnd: '28/05/2024' }"  <!-- Configuration for start date restrictions in range selection -->
  [endMinMaxConfig]="{ maxEnd: '10/07/2024' }"  <!-- Configuration for end date restrictions in range selection -->
>
</bm-datepicker>
```
