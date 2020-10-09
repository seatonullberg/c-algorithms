test_sources = files([
    'alloc-testing.c',
    'framework.c',
])

test_cases = [
    'alloc-testing',
    'arraylist',
    'avl-tree',
    'binary-heap',
    'binomial-heap',
    'bloom-filter',
    'compare-functions', 
    'hash-functions', 
    'hash-table', 
    'list', 
    'queue', 
    'rb-tree', 
    'set', 
    'slist', 
    'sortedarray', 
    'trie',
]

foreach case: test_cases
    test(
        case, 
        executable(
            'test-@0@'.format(case), 
            'test-@0@.c'.format(case),
            test_sources,
            sources,
            include_directories: [inc, test_inc],
        )
    )
endforeach