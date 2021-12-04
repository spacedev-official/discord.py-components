# ActionRow

The ActionRow component (you can use an array for this)\
**Extends:** [`py-cord-components.Component`](../componentmessage.md)``

{% tabs %}
{% tab title="Parameters" %}
| \*components                           |
| -------------------------------------- |
| Components the ActionRow will contain. |
{% endtab %}

{% tab title="Attributes" %}
| components                                     |
| ---------------------------------------------- |
| The list of components the ActionRow contains. |
{% endtab %}

{% tab title="Methods" %}
| to\_dict                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Gets the component information required for API requests in dict form.</p><p></p><p><strong>Returns: <code>dict</code></strong></p> |

| from\_dict                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Creates component instance from json.<br><br>This is a static method.</p><p></p><p><strong>Parameters:</strong></p><ul><li><strong>data</strong> (<code>dict</code>) - The json to construct button from.</li></ul><p><strong>Returns:</strong> <a href="pets.md"><code>py-cord-components.ActionRow</code></a><code></code></p> |

| append                             |
| ---------------------------------- |
| Adds a component to the ActionRow. |
{% endtab %}
{% endtabs %}
