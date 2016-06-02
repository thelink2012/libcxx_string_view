# std::basic_string_view

This is a implementation of `std::basic_string_view`.

It's simply the implementation on libcxx repository with licxx-specific stuff replaced (or *expanded*, for macros) with a compiled independent counterpart.

`std::hash<>` specialization and `std::quoted` overload were removed since we can't really implement those in a natural but compiler independent way.
