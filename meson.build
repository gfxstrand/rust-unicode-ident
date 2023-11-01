project(
  'unicode-ident',
  'rust',
  version : '1.0.6',
  license : '(MIT or Apache-2.0) AND Unicode-DFS-2016)',
  default_options : ['rust_std=2018', 'build.rust_std=2018'],
)

lib = static_library(
  'unicode_ident',
  'src/lib.rs',
  rust_crate_type : 'rlib',
  native : true,
)
