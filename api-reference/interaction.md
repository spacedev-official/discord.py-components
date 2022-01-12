# Interaction

Contains information about components interact event.

{% tabs %}
{% tab title="Attributes" %}
| client                                                                                            |
| ------------------------------------------------------------------------------------------------- |
| <p>The <code>PycordComponents</code> instance.<br><br><strong>Type: </strong><code>str</code></p> |

| user                                                                                                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p>The user who interacted with the component.<br><br><strong>Type: </strong>Optional[<code>discord.User</code>, <code>discord.Member</code>]<br><strong>Alias: </strong><code>member</code></p> |

| component                                                                                                                                                                                                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p>The component with which the user interacted.<br>This is <code>dict</code> if the component was in an ephemeral message.<br><br><strong>Type: </strong><code><a href="component/README.md"><code>py-cord-components.Component</code></a></code></p> |

| custom_id                                                                                    |
| -------------------------------------------------------------------------------------------- |
| <p>The custom id of interacted component.<br><br><strong>Type: </strong><code>str</code></p> |

| values                                                                                                     |
| ---------------------------------------------------------------------------------------------------------- |
| <p>The values of interacted select.<br><br><strong>Type: </strong>Optional\[List\[<code>str</code>\]\]</p> |

| component_type                                                                                    |
| ------------------------------------------------------------------------------------------------- |
| <p>The component type of interacted component.<br><br><strong>Type: </strong><code>int</code></p> |

| raw_data                                                                       |
| ------------------------------------------------------------------------------ |
| <p>The request's raw data.<br><br><strong>Type: </strong><code>dict</code></p> |

| message                                                                                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p>The mesage with the component interacted.<br><br><strong>Type: </strong><code><a href="componentmessage.md"><code>py-cord-components.ComponentMessage</code></a></code></p> |

| guild                                                                                          |
| ---------------------------------------------------------------------------------------------- |
| <p>The component message’s guild.<br><br><strong>Type: </strong><code>discord.Guild</code></p> |

| channel                                                                                                    |
| ---------------------------------------------------------------------------------------------------------- |
| <p>The component message’s channel.<br><br><strong>Type: </strong><code>discord.abc.Messageable</code></p> |

| interaction_id                                                              |
| --------------------------------------------------------------------------- |
| <p>The interaction’s ID.<br><br><strong>Type: </strong><code>str</code></p> |

| interaction_token                                                              |
| ------------------------------------------------------------------------------ |
| <p>The interaction’s token.<br><br><strong>Type: </strong><code>str</code></p> |

| responded                                                            |
| -------------------------------------------------------------------- |
| <p>If responded?<br><br><strong>Type: </strong><code>bool</code></p> |

| deferred                                                            |
| ------------------------------------------------------------------- |
| <p>If deferred?<br><br><strong>Type: </strong><code>bool</code></p> |
{% endtab %}

{% tab title="Methods" %}

| respond                                                            |
| ------------------------------------------------------------------- |
| <p>Sends a response to Discord.<br><br><strong>Parameters: </strong><br><strong>type </strong>(<code>int</code>) - The interaction’s type. (4 ~ 6) Defaults to <code>4</code>.<br><strong>ephemeral </strong>(<code>bool</code> defaults to <code>True</code>) - If the response is ephemeral.<br><strong>content </strong>(<code>str</code>) - The response message's content.<br><strong>embed </strong>(<code>discord.Embed</code>) - The response message’s embed.<br><strong>embeds </strong>(List\[<code>discord.Embed</code>\]) - The response message’s embeds.<br><strong>suppress </strong>(<code>bool</code>)<br><strong>file </strong>(<code>discord.File</code>) - The response message’s file.<br><strong>files </strong>(List\[<code>discord.File</code>\]) - The response message's files.<br><strong>type </strong>(<code>int</code>) - The interaction’s type. (4 ~ 6) Defaults to <code>4</code>.<br><strong>type </strong>(<code>int</code>) - The interaction’s type. (4 ~ 6) Defaults to <code>4</code>.<br><strong>type </strong>(<code>int</code>) - The interaction’s type. (4 ~ 6) Defaults to <code>4</code>.</p> |
{% endtab %}
{% endtabs %}