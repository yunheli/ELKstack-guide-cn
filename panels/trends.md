# trends

Status: Beta

A stock-ticker style representation of how queries are moving over time. For example, if the time is 1:10pm, your time picker was set to "Last 10m", and the "Time Ago" parameter was set to "1h", the panel would show how much the query results have changed since 12:00-12:10pm

## parameters

* ago
    A date math formatted string describing the relative time period to compare the queries to.
* arrangement
    ‘horizontal’ or ‘vertical’
* spyable
    Set to false to disable the inspect icon

**queries**

* queries object
    This object describes the queries to use on this panel.
  * queries.mode
    Of the queries available, which to use. Options: `all, pinned, unpinned, selected`
  * queries.ids
    In `selected` mode, which query ids are selected.