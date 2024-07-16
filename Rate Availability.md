# Rate Availability

Rate availability controls which rate codes are available for booking on specific dates. protel Front Office provides flexible options for managing rate availability, including the standard version and the extended protel Multi Strategy.

## Standard Version:

* **Calendar View:** Displays a calendar-based overview of all rates for a given month.
* **Rate Code or Detail Level:** Manage availability for entire rate codes or individual rate code details.
* **Strategies:**  Apply different strategies to block rates, restrict arrivals, set minimum stays, and more. 

## protel Multi Strategy:

* **Table View:**  Shows all defined strategies in a table format.
* **Advanced Filtering:**  Filter strategies by rate code, rate code detail, rate group, yield level, or combinations thereof.
* **Multiple Strategies:**  Define multiple strategies for different rate levels, with more specific strategies taking precedence.

## Setting Strategies:

1. **Choose the version:**  Decide whether to use the standard version or protel Multi Strategy.
2. **Select a rate code/detail:** Choose the rate code or detail you want to manage.
3. **Define the period:** Specify the date range for the strategy.
4. **Select the strategy:**  Choose a strategy from the dropdown list and enter any required parameters (e.g., minimum stay, occupancy).
5. **Set the strategy:** Click "Set" to apply the strategy.

## Strategies and Their Meaning:

* **Open:**  Rate is available for booking.
* **Closed:** Rate is unavailable.
* **Closed for Arrivals:**  Rate cannot be booked for arrivals on the chosen dates.
* **Minimum Stay:**  Requires a minimum length of stay.
* **Minimum Length of Stay on Arrival:** Defines a minimum stay for specific arrival days.
* **Minimum Remaining Length of Stay:** Sets a minimum stay for reservations extending beyond a certain date.
* **Stay Length Must Be Between:**  Restricts bookings to stays within a specified length range.
* **Minimum of Adults:** Requires a minimum number of adults.
* **Open When Staying Days or a Multiple Of:**  Makes rates available for specific stay lengths (e.g., 7 nights for the price of 6). 
* **Maximum Sell (SQL only):**  Limits the number of bookings for a specific rate.
* **Closed if Occupancy Exceeds Percent (SQL only):**  Blocks rates when occupancy reaches a certain threshold.
* **Open When Occupancy Percent (SQL only):**  Makes rates available only within a defined occupancy range. 
* **Closed at Occ. > Or Days Before Arrival (SQL only):**  Combines occupancy and days-before-arrival restrictions.
* **Closed When Room Type Occupancy Exceeds Percent (SQL only):**  Blocks rates based on room type occupancy.
* **Closed > Days Before Arrival (SQL only):**  Used for early bird offers, blocking rates close to the arrival date.

## Publishing to GDS:

If you are connected to a GDS, use the "Publish to GDS" button to transfer rate availability changes.

## Benefits:

* Optimized rate management and revenue generation.
* Flexible control over rate availability based on demand, occupancy, and market conditions.
* Improved pricing consistency across all distribution channels.

## Tips:

* Carefully plan and define your rate availability strategies.
* Regularly review and adjust strategies to reflect changing market dynamics.
* Consult with your revenue management team or yield management provider for optimal strategies.