+++
date = "2017-03-03T20:23:43-05:00"
title = "Options"
weight = "6"
+++

An always up-to-date list of options may be found at <a href="https://github.com/chmln/flatpickr/blob/master/src/types/options.ts#L19" target="_blank">`options.ts`</a>

<table class="options">
    <thead>
        <tr>
            <th>Config Option</th>
            <th>Type</th>
            <th>Default</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>altFormat</td>
            <td>String</td>
            <td>"F j, Y"</td>
            <td>Exactly the same as date format, but for the altInput field</td>
        </tr>
        <tr>
            <td>altInput</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Show the user a readable date (as per altFormat), but return something totally different to the server.</td>
        </tr>
        <tr>
            <td>altInputClass</td>
            <td>String</td>
            <td>""</td>
            <td>This class will be added to the input element created by the altInput option. &nbsp;Note that&nbsp;<code>altInput</code>&nbsp;already inherits classes from the original input.</td>
        </tr>
        <tr>
            <td>allowInput</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Allows the user to enter a date directly into the input field. By default, direct entry is disabled.</td>
        </tr>
        <tr>
            <td>allowInvalidPreload</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Allows the preloading of an invalid date. When disabled, the field will be cleared if the provided date is invalid</td>
        </tr>
        <tr>
            <td>appendTo</td>
            <td>HTMLElement</td>
            <td>null</td>
            <td>Instead of&nbsp;<code>body</code>, appends the calendar to the specified node instead*.</td>
        </tr>
        <tr>
            <td>ariaDateFormat</td>
            <td>String</td>
            <td>"F j, Y"</td>
            <td>Defines how the date will be formatted in the&nbsp;<code>aria-label</code> for calendar days, using the same tokens as&nbsp;<code>dateFormat</code>. If you change this, you should choose a value that will make sense if a screen reader reads it out loud.</td>
        </tr>
        <tr>
            <td>conjunction</td>
            <td>String</td>
            <td>null</td>
            <td>When in "multiple" mode, <code>conjunction</code> is used to separate dates in the entry field.</td>
        </tr>
        <tr>
            <td>clickOpens</td>
            <td>Boolean</td>
            <td>true</td>
            <td>Whether clicking on the input should open the picker. You could disable this if you wish to open the calendar manually with<code>.open()</code></td>
        </tr>
        <tr>
            <td>dateFormat</td>
            <td>String</td>
            <td>"Y-m-d"</td>
            <td>A string of characters which are used to define how the date will be displayed in the input box. The supported characters are defined in&nbsp;<a href="/formatting">the table below</a>.</td>
        </tr>
        <tr>
            <td><strong>defaultDate</strong></td>
            <td>String</td>
            <td>null</td>
            <td>
            <p>Sets the initial selected date(s). </p>
            <p>If you're using <code>mode: "multiple"</code> or a range calendar supply an <code>Array</code> of <code>Date</code> objects or an Array of date strings which follow your <code>dateFormat</code>.</p>
            <p>Otherwise, you can supply a single Date object or a date string.</p>
            </td>
        </tr>
        <tr>
            <td>defaultHour</td>
            <td>Number</td>
            <td>12</td>
            <td>
                <p>Initial value of the hour element.</p>
            </td>
        </tr>
        <tr>
            <td>defaultMinute</td>
            <td>Number</td>
            <td>0</td>
            <td>
                <p>Initial value of the minute element.</p>
            </td>
        </tr>
        <tr>
            <td>disable</td>
            <td>Array</td>
            <td>[]</td>
            <td>
                See&nbsp;<a href="/examples/#disabling-specific-dates">Disabling dates</a>
            </td>
        </tr>
        <tr>
            <td>disableMobile</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Set&nbsp;<code>disableMobile</code>&nbsp;to true to always use the non-native picker.<br>
            By default, flatpickr utilizes native datetime widgets unless certain options (e.g. disable) are used.</td>
        </tr>
        <tr>
            <td>enable</td>
            <td>Array</td>
            <td>undefined</td>
            <td>
                See&nbsp;<a href="/examples/#disabling-all-dates-except-select-few">Enabling dates</a>
            </td>
        </tr>
        <tr>
            <td>enableTime</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Enables time picker</td>
        </tr>
        <tr>
            <td>enableSeconds</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Enables seconds in the time picker.</td>
        </tr>
        <tr>
            <td>formatDate</td>
            <td>Function</td>
            <td>null</td>
            <td>Allows using a custom date formatting function instead of the built-in handling for date formats using&nbsp;<code>dateFormat</code>,&nbsp;<code>altFormat</code>, etc.</td>
        </tr>
        <tr>
            <td>hourIncrement</td>
            <td>Integer</td>
            <td>1</td>
            <td>Adjusts the step for the hour input (incl. scrolling)</td>
        </tr>
        <tr>
            <td>inline</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Displays the calendar inline</td>
        </tr>
        <tr>
            <td>maxDate</td>
            <td>String/Date</td>
            <td>null</td>
            <td>The maximum date that a user can pick to (inclusive).</td>
        </tr>
        <tr>
            <td>minDate</td>
            <td>String/Date</td>
            <td>null</td>
            <td>The minimum date that a user can start picking from (inclusive).</td>
        </tr>
        <tr>
            <td>minuteIncrement</td>
            <td>Integer</td>
            <td>5</td>
            <td>Adjusts the step for the minute input (incl. scrolling)</td>
        </tr>
        <tr>
            <td>mode</td>
            <td>String</td>
            <td>"single"</td>
            <td><code>"single"</code>,&nbsp;<code>"multiple"</code>, or&nbsp;<code>"range"</code></td>
        </tr>
        <tr>
            <td>nextArrow</td>
            <td>String</td>
            <td><code>&gt;</code></td>
            <td>HTML for the arrow icon, used to switch months.</td>
        </tr>
        <tr>
            <td>noCalendar</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Hides the day selection in calendar.<br>
            Use it along with&nbsp;<code>enableTime</code>&nbsp;to create a time picker.</td>
        </tr>
        <tr>
            <td>onChange</td>
            <td>Function, [functions]</td>
            <td>null</td>
            <td>
                Function(s) to trigger on every date selection. See&nbsp;<a href="/events/#onchange">Events API</a>
            </td>
        </tr>
        <tr>
            <td>onClose</td>
            <td>Function, [functions]</td>
            <td>null</td>
            <td>
                Function(s) to trigger on every time the calendar is closed. See&nbsp;<a href="/events/#onclose">Events API</a>
            </td>
        </tr>
        <tr>
            <td>onOpen</td>
            <td>Function, [functions]</td>
            <td>null</td>
            <td>
                Function(s) to trigger on every time the calendar is opened. See&nbsp;<a href="/events/#onopen">Events API</a>
            </td>
        </tr>
        <tr>
            <td>onReady</td>
            <td>Function, [functions]</td>
            <td>null</td>
            <td>
                Function to trigger when the calendar is ready. See&nbsp;<a href="/events/#onready">Events API</a>
            </td>
        </tr>
        <tr>
            <td>parseDate</td>
            <td>Function</td>
            <td>false</td>
            <td>Function that expects a date string and must return a Date object</td>
        </tr>
        <tr>
            <td>position</td>
            <td>String</td>
            <td>"auto"</td>
            <td>
                Where the calendar is rendered relative to the input vertically and horizontally. In the format of "[vertical] [horizontal]". Vertical can be <code>auto</code>, <code>above</code> or <code>below</code> (required). Horizontal can be <code>left</code>, <code>center</code> or <code>right</code>.<br><br>e.g. <code>"above"</code> or <code>"auto center"</code>
             </td>
        </tr>
        <tr>
            <td>positionElement</td>
            <td>Element</td>
            <td>null</td>
            <td>
                The element off of which the calendar will be positioned.
             </td>
        </tr>
        <tr>
            <td>prevArrow</td>
            <td>String</td>
            <td><code>&lt;</code></td>
            <td>HTML for the left arrow icon.</td>
        </tr>
        <tr>
            <td>shorthandCurrentMonth</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Show the month using the shorthand version (ie, Sep instead of September).</td>
        </tr>
        <tr>
            <td>static</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Position the calendar inside the wrapper and next to the input element*.</td>
        </tr>
        <tr>
            <td>showMonths</td>
            <td>Integer</td>
            <td>1</td>
            <td>The number of months to be shown at the same time when displaying the calendar.</td>
        </tr>
        <tr>
            <td>time_24hr</td>
            <td>boolean</td>
            <td>false</td>
            <td>Displays time picker in 24 hour mode without AM/PM selection when enabled.</td>
        </tr>
        <tr>
            <td>weekNumbers</td>
            <td>Boolean</td>
            <td>false</td>
            <td>Enables display of week numbers in calendar.</td>
        </tr>
        <tr>
            <td>wrap</td>
            <td>Boolean</td>
            <td>false</td>
            <td>
                <a href="/examples/#flatpickr-external-elements">Custom elements and input groups</a>
            </td>
        </tr>
        <tr>
            <td>monthSelectorType</td>
            <td>String</td>
            <td>"dropdown"</td>
            <td>
                How the month should be displayed in the header of the calendar.<br><br><code>"dropdown"</code> or <code>"static"</code><br><br>If <code>showMonths</code> has a value greater than 1, the month is always shown as static.
            </td>
        </tr>
    </tbody>
</table>

<small>* Attaching the calendar to a specific element makes it depend on that element's position and style. If the calendar is not positioned as expected, check the CSS rules of the container.</small>
