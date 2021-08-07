---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<p>
This Connector is used to connect and ingest data from Whitebox API. It is for internal use, and users will be required to obtain credentials (api_user, api_key) internally. 
</p>
<p>
Each of the data point correspond to an order item. Each order item will contain information such as order number, product, sales, quantity, etc. Each data point is created by joining data from several APIs. The join key used is the ID of each data object. For example: order item is joined with product through product_id.
</p>
<p>
Some of the data objects can't be joined because there is no one-to-one or many-to-one relationship between order item and that data object. For example: order items and base_units has a one-to-many relationship (one order item maps to multiple base_units), thus the details of base_units can't be mapped.
</p>
<p>
Please check out the <a href="/ScriptConnector/policy/">Privacy Policy</a> and <a href="/ScriptConnector/term/" >Terms of Use</a> before using. Thank you!
</p>