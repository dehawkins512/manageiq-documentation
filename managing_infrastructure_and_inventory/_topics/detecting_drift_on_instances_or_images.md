# Detecting Drift on Instances or Images

The configuration of an instance might change over time. **Drift** is
the comparison of an instance to itself at different points in time. The
instance needs to be analyzed at least twice to collect this
information. Detecting drift provides you the following benefits:

  - See the difference between the last known state of a machine and its
    current state.

  - Review the configuration changes that happen to a particular
    instance between multiple points in time.

  - Review the association changes that happen to a particular instance
    between multiple points in time.

  - Review the classification changes that happen to an instance between
    two time checks.

  - Capture the configuration drifts for a single instance across a time
    period.

Detect drift on instances or images:

1.  Browse to menu: **Compute > Clouds > Instances**.

2.  Click the accordion for the item to view drift.

3.  Click on the item to view its **Summary**.

4.  From the **Relationships** area in the **Summary**, click **Drift
    History**.

5.  Click the checkboxes for the analyses to compare.

6.  Click ![1946](../images/1946.png) (**Select up to 10 timestamps for
    Drift Analysis**)\] at the top of the screen. The results display.

7.  Check the **Drift** sections on the left to view in your comparison.

8.  Click **Apply**.

9.  The following descriptions pertain to the **Expanded View**
    ![2023](../images/2023.png). Whether you see the value of a property
    or an icon representing the property depends on the properties type.

      - A property displayed in the same color as the base means the
        compared analysis matches the base for that property.

      - A property displayed in a different color from the base means
        the compared analysis does not match the base for that property.

10. If you are in the **Compressed View** ![2024](../images/2024.png), the
    values of the properties are not displayed. All items are described
    by the icons shown below.

      - A ![2150](../images/2150.png) (**checkmark**) means that the
        compared analysis matches the base for that property. If you
        hover over it, the value of the property will display.

      - A ![2177](../images/2177.png) (**triangle**) means the compared
        analysis does not match the base for that property. If you hover
        over it, the value of the property displays. Click the minus
        sign next to the sections name to collapse it.

11. To limit the scope of the view, you have three buttons in the
    **Resource** button area.

      - Click ![2178](../images/2178.png) (**All attributes**) to see all
        attributes of the sections you selected.

      - Click ![2204](../images/2204.png) (**Attributes with different
        values**) to see only the attributes that are different across
        the drifts.

      - Click ![2148](../images/2148.png) (**Attributes with the same
        values**) to see only the attributes that are the same across
        drifts.

12. To limit the mode of the view, there are two buttons in the
    **Resource** button area.

      - Click ![2022](../images/2022.png) (**Details Mode**) to see all
        details for an attribute.

      - Click ![2025](../images/2025.png) (**Exists Mode**) to only see if
        an attribute exists compared to the base or not. This only
        applies to attributes that can have a Boolean property. For
        example, a user account exists or does not exist, or a piece of
        hardware that does or does not exist.

This creates a drift analysis. Download the data or create a report from
your drift for analysis using external tools.
