Reading
“The Past, Present, and Future of Local Storage for Web Applications”

-storing key/value pairs locally on the client web browser
-data stored in local storage is a string
- clearing local storage
    interface Storage {
        deleter void removeItem(in DOMString key)
        void clear()
    }

-calling remove item with a non-existent key will do nothing

-5mb is the max amount of storage
