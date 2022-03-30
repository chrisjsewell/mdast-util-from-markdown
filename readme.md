# mdtoken-to-mdast

mdast utility to compile micromark tokens.

**IMPORTANT**: This is a fork of [mdast-util-from-token](https://github.com/syntax-tree/mdast-util-from-markdown),
which exposes the `compiler` function for import,
and not affiliated directly with unified.

Unfortunately, a request to the core package for this was rejected: [syntax-tree#29 (comment)](https://github.com/syntax-tree/mdast-util-from-markdown/issues/29#issuecomment-1078782161).
But it is currently required for [unified-myst](https://github.com/executablebooks/unified-myst).
