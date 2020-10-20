Read
setState explained
    -  reconciliation. The reconciliation process is the way React updates the DOM
        We have a search component that displays a search term
        That search term is currently empty
        The user submits a search term
        That term is captured and stored by setState as a value
        Reconciliation takes place and React notices the change in value
        React instructs the search component to update the value and the search term is merged in
Lists and Keys
    - keys
        -Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:
        -Keys Must Only Be Unique Among Siblings
Typechecking Props
Components and Props
handling events
snapshot testing
React Testing Libr