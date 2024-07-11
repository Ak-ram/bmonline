
## `<bm-accordion>` Component Documentation

### Usage

   ```html
   <bm-accordion [allowMultiple]="boolean" [collapseAll]="boolean">
     <bm-accordion-item [variant]="string" [expanded]="boolean" [toggleLocked]="boolean" (isExpanded)="isExpan($event)">
       <span startContent>Title</span>
          Description
     </bm-accordion-item>
     // ... and another bm-accordion-items as you need  
   </bm-accordion>
   ```

### Description

- **`<bm-accordion>`:**
  - Contains multiple `<bm-accordion-item>` elements to create a list of collapsible panels.
  - **Attributes:**
    - **`[allowMultiple]` (boolean):**
      - Allows multiple accordion items to be expanded simultaneously, if `false` then opening one accordion item will automatically collapse the others.
    - **`[collapseAll]` (boolean):**
      - Collapses all accordion items initially if set to `true`.
    
- **`<bm-accordion-item>`:**
  - Represents each panel in the accordion.
  - **Attributes:**
    - **`[expanded]` (boolean):**
      - Determines if the item is initially expanded (`true`) or collapsed (`false`).
    - **`[toggleLocked]` (boolean):**
      - Prevents users from toggling the expansion state if set to `true`.
    - **`[variant]` (string):**
      - Sets the visual style of the accordion item (`'elevated'`, `'outlined'`, etc.).

- **Event Handling:**
  - `(isExpanded)`: Event emitted when an accordion item's expansion state changes, $event is a boolean value which is true if the item is expanded and false if the item is collapsed, so you can use function like (isExpanded()) to perform actions when item is expanded and collpased

### Methods

- **`expandAll()`:**
  - Expands all accordion items programmatically.
  
- **`collapseAll()`:**
  - Collapses all accordion items programmatically.
  
- **`add()`:**
  - Adds new items dynamically to the accordion (if applicable).

### Usage Notes

- Ensure to bind necessary event handlers like `(isExpanded)` to respond to user interactions or state changes.
- Customize each `<bm-accordion-item>` with appropriate content and styling based on your application's design guidelines.

---

This documentation snippet provides a comprehensive guide on how to effectively utilize the `<bm-accordion>` component in your Angular application, covering all relevant attributes, usage examples, and best practices. Adjust the examples and descriptions according to your specific project requirements and design guidelines.
