---
title: lists
overview: lists aspect configuration schema

order: 1160

layout: docs
type: markdown
---


<a name="aspect.ListsParams"></a>
### ListsParams
Configures a lists aspect.

Example:
   kind: lists
   params:
	    blacklist: true
     checkExpression: source.ip

<table>
 <tr>
  <th>Field</th>
  <th>Type</th>
  <th>Description</th>
 </tr>
<a name="aspect.ListsParams.blacklist"></a>
 <tr>
  <td><code>blacklist</code></td>
  <td>bool</td>
  <td>blacklist determines if this behaves like a blacklist default is whitelist</td>
 </tr>
<a name="aspect.ListsParams.checkExpression"></a>
 <tr>
  <td><code>checkExpression</code></td>
  <td>string</td>
  <td>checkExpression is the expression evaluated at runtime to derive the value that is checked against the list</td>
 </tr>
</table>
