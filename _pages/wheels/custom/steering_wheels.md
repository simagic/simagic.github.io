---
#layout: single
layout: page
title: Custom Wheels
permalink: /hardware/wheels/
has_children: true
---

# Wheel overview table
Copy from [Google Doc](https://docs.google.com/spreadsheets/d/1HbCalQYmV4_UasplthMmN3y-ymeUfvX5UfqmqaYK0Uk/htmlview){:target="_blank"}
<table>
    <tbody>
    <tr style="color:#eaeaea; background-color:#51555d; border-bottom:2px solid #3d4046;">
            <th>Brand</th>
            <th>Model</th>
            <th>LINK</th>
            <th>Style</th>
            <th>Screen</th>
            <th>Width MM</th>
            <th>RETAIL EU</th>
            <th>RETAIL US</th>
    </tr>
        {% for wheel in site.data.ywheels %}
          <tr>
            <td style="word-break:break-all;">{{ wheel.Brand }}</td>
            <td style="word-break:break-all;">{{ wheel.Model }}</td>
            <td style="word-break:break-all;">{{ wheel.LINK }}</td>
            <td style="word-break:break-all;">{{ wheel.Style }}</td>
            <td style="word-break:break-all;">{{ wheel.Screen }}</td>
            <td style="word-break:break-all;">{{ wheel.Width_MM }}</td>
            <td style="word-break:break-all;">{{ wheel.RETAIL_EU }}</td>
            <td style="word-break:break-all;">{{ wheel.RETAIL_US }}</td>
          </tr>
        {% endfor %}
    </tbody>
</table>