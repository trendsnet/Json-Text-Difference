# Json Text Difference

- ![#27ae60](https://placehold.it/15/27ae60/000000?text=+) `New element`
- ![#e67e22](https://placehold.it/15/e67e22/000000?text=+) `Updated element`
- ![#c0392b](https://placehold.it/15/c0392b/000000?text=+) `Removed element`

![Json difference](https://knil.gq/img/json-diff-text.png)

### Usage

Import the script file `jdd.js` (or `jdd.min.js`) into your script folder in your project.
Note* jQuery is also required.

```html
<script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>
<script src="jdd.js"></script>
```

Then, just specify the ID's of the blocks that contain the json.

```javascript
  const leftBlockId = $('#left').attr('id');
  const rightBlockId = $('#right').attr('id');
  
  $(document).jdd(leftBlockId, rightBlockId);
```