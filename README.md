# fbox
## A simple flex-box thing


`<f-row>`, `<f-col>`, and `<f-box>` are element styles that make flex-box layouts a bit more like `<table>` layouts. Check out the [the examples](https://rawgit.com/spalger/fbox/master/examples/index.html) page for details.

<table>
  <tr>
    <td>
      <code>&lt;f-col&gt;</code>
    </td>
    <td>
      mimics the table tag, lays its children out vertically

      <dl>
        <dt><code>[align="center"]</code></dt>
        <dd>accepts <code>"top"</code>, <code>"center"</code>, or <code>"bottom"</code></dd>
      </dl>
    </td>
  </tr>
  <tr>
    <td>
      <code>&lt;f-row&gt;</code>
    </td>
    <td>
      mimics the tr tag, lays its children out horizontally

      <dl>
        <dt><code>[align="center"]</code></dt>
        <dd>accepts <code>"left"</code>, <code>"center"</code>, or <code>"right"</code></dd>
      </dl>
    </td>
  </tr>
  <tr>
    <td>
      <code>&lt;f-box&gt;</code>
    </td>
    <td>
      mimics the td tag, expected inside of <code>&gt;f-col&lt;</code> and <code>&gt;f-row>&lt;</code> elements
    </td>
  </tr>
</table>