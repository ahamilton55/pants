# Copyright 2015 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_tests(
  name='addressable',
  sources=['test_addressable.py'],
  dependencies=[
    'src/python/pants/engine/exp:addressable',
  ]
)


python_tests(
  name='struct`',
  sources=['test_struct.py'],
  dependencies=[
    'src/python/pants/build_graph',
    'src/python/pants/engine/exp:objects',
    'src/python/pants/engine/exp:struct',
  ]
)

python_tests(
  name='engine',
  sources=['test_engine.py'],
  dependencies=[
    'src/python/pants/base:cmd_line_spec_parser',
    'src/python/pants/build_graph',
    'src/python/pants/engine/exp/examples:planners',
    'src/python/pants/engine/exp:engine',
    'src/python/pants/engine/exp:scheduler',
  ]
)

python_tests(
  name='graph',
  sources=['test_graph.py'],
  dependencies=[
    'src/python/pants/build_graph',
    'src/python/pants/engine/exp:graph',
    'src/python/pants/engine/exp:mapper',
    'src/python/pants/engine/exp:parsers',
    'src/python/pants/engine/exp:struct',
  ]
)

python_tests(
  name='mapper',
  sources=['test_mapper.py'],
  dependencies=[
    'src/python/pants/build_graph',
    'src/python/pants/engine/exp:mapper',
    'src/python/pants/engine/exp:parsers',
    'src/python/pants/engine/exp:struct',
    'src/python/pants/util:contextutil',
    'src/python/pants/util:dirutil',
  ]
)

python_tests(
  name='parsers',
  sources=['test_parsers.py'],
  dependencies=[
    'src/python/pants/engine/exp:objects',
    'src/python/pants/engine/exp:parsers',
  ]
)

python_tests(
  name='scheduler',
  sources=['test_scheduler.py'],
  dependencies=[
    'src/python/pants/build_graph',
    'src/python/pants/engine/exp/examples:planners',
    'src/python/pants/engine/exp:engine',
    'src/python/pants/engine/exp:scheduler',
  ]
)
