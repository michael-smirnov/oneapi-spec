======================================
Non-member lexicographical comparisons
======================================

.. code:: cpp

    template <typename Key, typename T, typename Compare, typename Allocator>
    bool operator<( const concurrent_map<Key, T, Compare, Allocator>& lhs,
                    const concurrent_map<Key, T, Compare, Allocator>& rhs )

**Returns**: ``true`` if ``lhs`` is lexicographically `less` than ``rhs``.

-----------------------------------------------------

.. code:: cpp

    template <typename Key, typename T, typename Compare, typename Allocator>
    bool operator<=( const concurrent_map<Key, T, Compare, Allocator>& lhs,
                    const concurrent_map<Key, T, Compare, Allocator>& rhs )

**Returns**: ``true`` if ``lhs`` is lexicographically `less or equal` than ``rhs``.

-----------------------------------------------------

.. code:: cpp

    template <typename Key, typename T, typename Compare, typename Allocator>
    bool operator>( const concurrent_map<Key, T, Compare, Allocator>& lhs,
                    const concurrent_map<Key, T, Compare, Allocator>& rhs )

**Returns**: ``true`` if ``lhs`` is lexicographically `greater` than ``rhs``.

-----------------------------------------------------

.. code:: cpp

    template <typename Key, typename T, typename Compare, typename Allocator>
    bool operator>=( const concurrent_map<Key, T, Compare, Allocator>& lhs,
                    const concurrent_map<Key, T, Compare, Allocator>& rhs )

**Returns**: ``true`` if ``lhs`` is lexicographically `greater or equal` than ``rhs``.
