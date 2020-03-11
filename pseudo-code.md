All Objectives to be met with jQuery -> DYNAMIC HTML/CSS

1. Display, Current day


2. Timeblocks, business hours, on the hour
    a. Color coding
        i. Past
        ii. Present
        iii. Future

    b. Event input, on timeblock click
        i. Save data to local storage

    c. Page/data persistence, on refresh.


# What is needed
- Page/Data persistence (Local Storage)
- Timeblocks, colorcoded
- Time tracking

# When page is loaded
- Current day is displayed at the top of the page
- Time blocks are displayed: colorcoded to current browser time
- Time blocks are displayed: Only Operation hours 0800-1800
- Saved data is displayed in time blocks

# When Time Block is clicked
- FIeld entry for event within Box
- On Confirm, PROMPT appears for event entry to timeblock, with any previous data



# ENCAP

Body

    Display id="currentDay"

        Current Day

    Timeblocks

        Span 0800-1800

        onClick

            Confirm

                CONFIRM

                    PROMPT for event

                        Any Previous data for block

                CANCEL

        Colorcoding based on time (.text-white)

            Past (.bg-secondary)

                Past Time

            Present (.bg-success)

                Current Time

            Future (.bg-info)

                Time yet to come

