# Select

The select component.\
**Extends:** [`py-cord-components.Component`](../componentmessage.md)``

{% tabs %}
{% tab title="Parameters" %}
| placeholder                                                                    |
| ------------------------------------------------------------------------------ |
| <p>The select's placeholder<br><br><strong>Type: </strong><code>str</code></p> |

| id                                                                            |
| ----------------------------------------------------------------------------- |
| <p>The select's custom id.<br><br><strong>Type: </strong><code>str</code></p> |

| options                                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>The select's options.<br><br><strong>Type: </strong><code>List[<a href="selectoption.md"><code>py-cord-components.SelectOption</code></a>]</code></p> |

| max_values                                                                     |
| ------------------------------------------------------------------------------ |
| <p>The select's max_values.<br><br><strong>Type: </strong><code>int</code></p> |

| min_values                                                                     |
| ------------------------------------------------------------------------------ |
| <p>The select's min_values.<br><br><strong>Type: </strong><code>int</code></p> |

| disabled                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Indicates if the select is disabled.<br><br><strong>Type: </strong><code>bool</code><br><strong>Default: </strong><code>False</code></p> |
{% endtab %}

{% tab title="Attributes" %}
| placeholder                                                                    |
| ------------------------------------------------------------------------------ |
| <p>The select's placeholder<br><br><strong>Type: </strong><code>str</code></p> |

| id                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------- |
| <p>The select's custom id.<br>If not provided, it is a random value.<br><br><strong>Type: </strong><code>str</code></p> |

| options                                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>The select's options.<br><br><strong>Type: </strong><code>List[<a href="selectoption.md"><code>py-cord-components.SelectOption</code></a>]</code></p> |

| max_values                                                                     |
| ------------------------------------------------------------------------------ |
| <p>The select's max_values.<br><br><strong>Type: </strong><code>int</code></p> |

| min_values                                                                     |
| ------------------------------------------------------------------------------ |
| <p>The select's min_values.<br><br><strong>Type: </strong><code>int</code></p> |

| disabled                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Indicates if the select is disabled.<br><br><strong>Type: </strong><code>bool</code><br><strong>Default: </strong><code>False</code></p> |
{% endtab %}

{% tab title="Methods" %}
| to\_dict                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Gets the component information required for API requests in dict form.</p><p></p><p><strong>Returns: <code>dict</code></strong></p> |

| from\_dict                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Creates component instance from json.<br><br>This is a static method.</p><p></p><p><strong>Parameters:</strong></p><ul><li><strong>data</strong> (<code>dict</code>) - The json to construct button from.</li></ul><p><strong>Returns:</strong> <a href="select.md"><code>py-cord-components.Select</code></a><code></code></p> |
{% endtab %}
{% endtabs %}