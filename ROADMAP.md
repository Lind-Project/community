# Roadmap

This roadmap describes the current state and planned direction of the
[Lind-Project](https://github.com/Lind-Project) across its repositories.
Timeframes are approximate.

## 1. Supported host environments

- **Now:** lind-wasm (Lind with the Wasm backend) runs in a Docker container on
  Linux, macOS, and Windows, and natively on Linux.
- **~6mo:** Add support for running in an SGX enclave. Improve quick start for
  the environment.

## 2. Isolation backends

- **Now:** The Wasm backend (via Wasmtime) is fully realized and runs
  application suites as complex as a full LAMP stack. We are factoring the
  backend-facing interface out of the Wasmtime-specific code so that additional
  backends can implement it.
- **~12mo:** An MPK backend that runs the core process model — cages,
  fork/exec/exit, and multi-cage execution — through 3i, reaching feature
  parity with the Wasm backend, including grate calls.

## 3. Performance

- **Now–12mo:** Establish performance baselines and optimize both the
  standalone and grate-call paths.

## 4. Running Lind as a shared object library

- **Now–6mo:** A prototype packages Lind itself as a shared library that a host
  application can load; within this embedded Lind, each untrusted library runs
  in its own cage. The host calls the library through the familiar
  shared-library interface, while the library executes fully isolated, with
  grates mediating its system calls. We are testing and hardening this support
  for real use in scientific library isolation.
