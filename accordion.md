
## `<bm-accordion>` Component Documentation

### Usage

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

### Note

- **`add()`:**
  - Adds new items dynamically to the accordion (if applicable).
---
