# Claude Code Performance Benchmark

Performance testing harness for Claude Code. Exercises Bash tool execution speed and throughput by running allowed commands as background tasks.

## Allowed Bash Commands

Claude can invoke these commands via the Bash tool. Performance is measured across sequential and parallel execution:

**Text Processing:** xargs, sed, sort, grep

**File Operations:** file, tree, stat, find, ls

**System Info:** ps, netstat, lsof, ss, pgrep, hostname, date, tput

**Checksums:** base64, md5sum, sha1sum, sha256sum

**Help & Documentation:** man, help, info

See README.md for full command reference and benchmark descriptions.

## Performance Metrics

Each command measures:
- Invocation latency (ms)
- Output parsing time
- Parallel execution efficiency (background tasks)
- Memory footprint

Ask Claude to run benchmarks directly via Bash tool commands documented in README.md.
