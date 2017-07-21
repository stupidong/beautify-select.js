# display-value-as-column.js


You can call your existing select by following method
```
    var items={
      "gandalf":"Gandalf",
      "harry":"Harry Potter",
      "jon":"Jon Snow",
      "tony":"Tony Stark",
      "steve":"Steven Rogers",
      "natasha":"Natasha Romanova",
    }

    $('#test-select').DisplayValueAsColumn(items);

```

You can apply it with html format, but you have to impliment your own event
```
<div class="display-value-as-column">
    <label>not required</label>
    <span>
    	<select class='display-select' >
      </select>
      <br>
    	<select class='value-select' >
    	</select>
    </span>
</div>
```

enjoy it

Test References: https://jsfiddle.net/stupidong/o6ep4ea2/

Beauty references: https://codepen.io/ericrasch/pen/zjDBx
