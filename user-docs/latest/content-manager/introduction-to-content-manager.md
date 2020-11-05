# Introduction to the Content Manager

The Content Manager is a core plugin of Strapi, which is always activated by default and can't be deleted. It is accessible either when the application is in environment development, or in production.

From the Content Manager, admin panel users can create, manage and distribute content based on the available content types. The latter must have been created beforehand using the Content-Types Builder (see Introduction to the Content-Types Builder). 

The Content Manager is divided into 2 parts in the admin panel: Collection types and Single types, both accessible from the main navigation.

::: tip TIP
If you have many content types, don't hesitate to click the search icon <Fa-Search /> to use a text search and find your content type more quickly.
:::

## Collection types

The Collection types part of the Content Manager, in the main navigation of the admin panel, displays the list of available collection types. For each available collection type, multiple entries can be created.

Clicking on a collection type redirects to its list view, which displays all entries created for that collection type.

[screenshot_list_view_collection_type]

From a collection type's list view, it is possible to:

- filter & search the entries,
- configure temporarily or permanently the settings of the list view,
- create a new entry,
- access the edit view of an available entry, from which admin panel users are allowed to:
  - write and edit the content of the entry,
  - delete the entry,
  - save and publish the content of the entry.

### Filtering & searching entries

If your collection type contains many entries, filters and search options can come in handy to find specific entries, instead of scrolling through the entire table of the list view.

#### Using a text search

At the top of the list view, a search bar is displayed. It allows you to make a textual search, that will looks for matching results as you type.

[screenshot_search]

#### Using filters

Right above the list view, a **Filters** button is displayed. It allows to set one or more condition-based filters.

[screenshot_active_filters]

To set a new filter:

1. Click on the **Filters** button.
2. Click on the 1st list box to choose the field on which the condition will be applied.
3. Click on the 2nd list box to choose the type of condition to apply.
4. Enter the value of the condition in the 3rd box.
5. Click on the **Apply** button.

[screenshot_new_condition]

When applied, the active filter is displayed right next to the **Filters** button.

::: tip NOTE
Conditions add to one another, meaning that if you set several conditions, only the entries that match all the conditions will be displayed.
:::

To delete a filter, click on the cross of that active filter.

[screenshot_delete_filter]

### Configuring list view settings

The configuration of the list view can be modified either permanently for all users, or temporarily, just for you.

To permanently modify the list view settings:

1. Click on the <Fa-Cog /> button, right above the table, on the right side of the list view.
2. Click on the **Configure the view** button.
3. Define your chosen new settings:

| Setting name           | Procedure                                                                                          |
| ---------------------- |----------------------------------------------------------------------------------------------------|
| Enable search          | Click on **ON** or **OFF** to able or disable the search.                                          |
| Enable filters         | Click on **ON** or **OFF** to able or disable filters.                                             |
| Enable bulk actions    | Click on **ON** or **OFF** to able or disable the multiple selection boxes in the list view table. |
| Entries per page       | Choose among the list box the number of entries per page.                                          |
| Default sort attribute | Choose the sorting field and type that will be applied by default.                                 |

4. Define what fields to display in the list view table, and in what order:
   - Click the + button to add a new field.
   - Click the x button to remove a field.
   - Click the :: button and drag and drop it to the place you want it to be displayed amond the other fields.
5. Click on the **Save** button.

::: tip NOTE
Modifying the configurations of a list view will only apply to that of the chosen collection type. E.g. Disabling the search or filters for a collection type does not mean that they will also be disabled for all other collection types.
:::

[screenshot_list_view_settings]

To temporarily choose what fields to display:

1. Click on the <Fa-Cog /> button, right above the table, on the right side of the list view.
2. In the Displayed Fields section, tick the boxes associated with the field you want to be displayed in the table.
3. Untick the boxes associated with the fields you want to remove from the table.

[screenshot_displayed_fields]

### Creating a new entry

To create a new entry for your collection type, click on the **Add New [Collection type name]** button on the top right left of the list view interface.


## Single types

The Single types part of the Content Manager, in the main navigation of the admin panel, displays the list of available single types. As single types are not created for multiple uses, there is only one entry per available single type.

Clicking on a single type directly redirect to its edit view. From this edit view, admin panel users are allowed to:

- write and edit the content of the single types,
- save and publish the content of the single type.

[screenshot_single_type_edit_view]