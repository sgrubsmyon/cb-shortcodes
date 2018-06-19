# cb-shortcodes
shortcodes for commons booking
Attention: some results contain personal user-data and should be displayed only on private pages for selected users!

php-files can be included in functions.php or installed as a plugin

shortcodes can be used in pages, posts and widgets

table sorting requires Plugin 'Table Sorter'

custom-shortcodes-cb-bookings-overviews.php:

[cb_bookings_preview]   coming bookings of all locations with booker's names (abbreviated)

[cb_bookings_overview]  bookings overview of 1 location with booker's contact data, parameter 'locid' and 'days' (max. days +/- today, default 15)

[cb_bookings_location]  bookings overview for location manager (CAF), parameter 'days' (max. days +/- today, default 15)
CAF = Plugin 'Custom Advanced Fields' (field 'user_locations': select 1-n locations in user profile)

custom-shortcodes-cb-items.php:

[cb_items_teaser]       items teaser (linked thumbnails , sorted by ID asc

[cb_items_teaser_cat]   items teaser (sorted and grouped by categories), optional parameter 'cat' (id)

[cb_items_date]         bookable items for 1 date (list), opt. parameter: 'addDays' (checked day after today) 

[cb_items_next_date]    next date with bookable items (list), opt. parameter: 'days' (max. checked days from today, default 30) and 'time' (0-24, time to switch checking from today to tomorrow, default 14)

[cb_items_available]    availability of all items for the next 30 days (sortable calendar table), opt. parameter 'desc' for table description

custom-shortcodes-cb-users1.php:

[cb_bookings_user]      user bookings summary (all subscriber bookings, sortable table)

COMING SOON: custom-shortcodes-statistics.php:

[cb_bookings_summary]   past bookings summary for all locations (sortable table plus chart) 

[cb_bookings_months]    past and future bookings summary for all items per month  (table and chart)

for more details see description on top of each php-file


