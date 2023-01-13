# Button

Button components

```js script
import '~/tokens/variables.css';
import './document-selector.css';
```

btn-1

<!-- ```js preview-story
export const btn1 = () => `
`;
``` -->

<div class="documents-selector">
  <div class="documents-selector__inline">
    <input
      type="text"
      placeholder="Escriba el nombre del archivo" 
      class="documents-selector__name"
      name="FileName"
      minlength="1"
      maxlength="70"
    >
    <div class="documents-selector__confirmation">
      <button 
        type="button" 
        class="documents-selector__confirmation-button"
      >
        CONFIRMAR
      </button>
      <button 
        type="button" 
        class="documents-selector__confirmation-cancel"
      >
        X
      </button>
    </div>
    <button
      type="button"
      class="documents-selector__file documents-selector__file--hide"
    > 
      <i class="documents-selector__file-icon icon-i-tutorial">↑</i>
        <div class="documents-selector__file-text">
        <div class="documents-selector__file-text-label">Elija el archivo</div>
        <div class="documents-selector__file-text-size">pdf (max 420mb)</div>
        </div>
        <input #fileInput type="file" class="documents-selector__file-input" />
    </button>
  </div>
  <input 
    type="text" 
    placeholder="Descripción" 
    class="documents-selector__descript"
    name="FileDescript" 
    minlength="1" 
    maxlength="70"
  >
</div>
