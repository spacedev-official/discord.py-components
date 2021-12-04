# ComponentMessage

## ComponentMessage

A message with components.\
**Extends:** `discord.Message`

{% tabs %}
{% tab title="Attributes" %}
The `discord.Message` attributes and

| components                                                                                                                                                                                                                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>The message’s components.</p><p></p><p><strong>Type:</strong> List[<a href="component/pets.md"><code>py-cord-components.ActionRow</code></a> | <a href="componentmessage.md"><code>py-cord-components.Component</code></a> | List[<a href="componentmessage.md"><code>py-cord-components.Component</code></a>]]</p> |

| ephemeral                                                                                |
| ---------------------------------------------------------------------------------------- |
| <p>If the message is ephemeral</p><p></p><p><strong>Type:</strong> <code>bool</code></p> |
{% endtab %}

{% tab title="Methods" %}
The `discord.Message` methods and (Also if `ephemeral` attribute is True, many methods are unable to use)

| get\_component                                                                                                                                                                                                                                                                           |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Finds a component in a message.<br></p><p><strong>Parameters:</strong></p><ul><li><strong>custom_id</strong> (<code>str</code>) - The component's custom id</li></ul><p><strong>Returns:</strong> <a href="component/"><code>py-cord-components.Component</code></a><code></code></p> |
{% endtab %}
{% endtabs %}
