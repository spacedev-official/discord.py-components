# SelectOption

Option on [Select](select.md).

{% tabs %}
{% tab title="Parameters" %}
| label                                                                    |
| ------------------------------------------------------------------------ |
| <p>The select's label<br><br><strong>Type: </strong><code>str</code></p> |

| value                                                                                                       |
| ----------------------------------------------------------------------------------------------------------- |
| <p>The select's value. (It is like a button's custom_id)<br><br><strong>Type: </strong><code>str</code></p> |

| emoji                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>The select's emoji.<br><br><strong>Type: </strong><code>discord.Emoji</code> \| <code>discord.PartialEmoji</code> \| <code>str</code></p> |

| description                                                                     |
| ------------------------------------------------------------------------------- |
| <p>The select's description.<br><br><strong>Type: </strong><code>str</code></p> |

| default                                                                                     |
| ------------------------------------------------------------------------------------------- |
| <p>If the option is selected initially.<br><br><strong>Type: </strong><code>bool</code></p> |
{% endtab %}

{% tab title="Attributes" %}
| label                                                                    |
| ------------------------------------------------------------------------ |
| <p>The select's label<br><br><strong>Type: </strong><code>str</code></p> |

| value                                                                                                       |
| ----------------------------------------------------------------------------------------------------------- |
| <p>The select's value. (It is like a button's custom_id)<br><br><strong>Type: </strong><code>str</code></p> |

| emoji                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>The select's emoji.<br><br><strong>Type: </strong><code>discord.Emoji</code> \| <code>discord.PartialEmoji</code> \| <code>str</code></p> |

| description                                                                     |
| ------------------------------------------------------------------------------- |
| <p>The select's description.<br><br><strong>Type: </strong><code>str</code></p> |

| default                                                                                     |
| ------------------------------------------------------------------------------------------- |
| <p>If the option is selected initially.<br><br><strong>Type: </strong><code>bool</code></p> |
{% endtab %}

{% tab title="Methods" %}
| to\_dict                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Gets the component information required for API requests in dict form.</p><p></p><p><strong>Returns: <code>dict</code></strong></p> |

| from\_dict                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Creates component instance from json.<br><br>This is a static method.</p><p></p><p><strong>Parameters:</strong></p><ul><li><strong>data</strong> (<code>dict</code>) - The json to construct button from.</li></ul><p><strong>Returns:</strong> <a href="option.md"><code>py-cord-components.SelectOption</code></a><code></code></p> |
{% endtab %}
{% endtabs %}
