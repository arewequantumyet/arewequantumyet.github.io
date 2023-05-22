# <span style="color:#800000">Not yet, but we have a few things.</span>

## Toolkits & Frameworks
[qoqo](https://github.com/HQSquantumsimulations/qoqo) qoqo is a toolkit to represent quantum circuits by [HQS Quantum Simulations](https://quantumsimulations.de). The qoqo toolkit contains a pure rust library (roqoqo) and a python wrapper around this library (qoqo). qoqo provides a thin runtime to run quantum measurements, a way to serialize quantum circuits and measurement information, and a collection of optional backends (e.g. [qoqo-quest](https://github.com/HQSquantumsimulations/qoqo-quest) for simulations with the C [QuEST](https://github.com/quest-kit/QuEST) library, [qoqo_qasm](https://github.com/HQSquantumsimulations/qoqo_qasm) for qasm export and [qoqo_aqt](https://github.com/HQSquantumsimulations/qoqo_aqt) for interfacing [AQT](https://www.aqt.eu) devices).

## Quantum Computer Cloud Service Bindings
[q1tsim](https://github.com/Q1tBV/q1tsim)
A gate-type simulator crate, that not just simulates, but
exports your circuits to Open QASM and C-Qasm, the former
being understood by IBM's Q Experience.

## Simulation & Circuit Design
[quantum](https://github.com/beneills/quantum)
A 5-qubit gate-type quantum computing simulator crate built for education.
It introduces you to the world of quantum simulator building by both code and documentation.

[rusq](https://github.com/hajifkd/rusq)
A gate-type quantum computing simulator inspired by Microsoft's Q#.

[rust-libquantum](https://github.com/mknyszek/rust-libquantum)
The Rust binding to libquantum, [a quantum simulator written in C](https://github.com/libquantum/libquantum).

[RustQIP](https://github.com/Renmusxd/RustQIP)
A gate-type simulation framework designed with graph building in mind.

[qasmsim](https://github.com/delapuente/qasmsim) A QASM interpreter and quantum simulator in Rust.
Written by Salvador de la Puente, member of IBM Research Quantum team.

[DQCsim](https://github.com/QE-Lab/dqcsim) The Delft Quantum & Classical simulator is a framework that can be used to tie components of quantum computer simulators together in a standardized yet flexible, developer-friendly, and reproducible way.

[Spinoza](https://github.com/QuState/spinoza) A quantum state simulator that is
one of the fastest open-source simulators. Spinoza is implemented using a
functional approach, and it has a `QuantumCircuit` object-oriented interface,
which partially matches Qiskit's interface.

## Post-Quantum Cryptography
[liboqs-rust](https://github.com/open-quantum-safe/liboqs-rust)
Rust bindings to liboqs, a [C package](https://github.com/open-quantum-safe/liboqs/) for quantum-safe KEM and digital signature alorithms.

[pqcrypto](https://github.com/rustpq/pqcrypto)
The Rust bindings to the C-implementations of quantum-safe encryption algorithms proposed to the NIST
[during this competition](https://csrc.nist.gov/projects/post-quantum-cryptography).

<span style="font-size:12px;font-style: italic">Compiled with love by [florianreinhard](https://florianreinhard.de). Did I miss something? Feel free to drop me a [line](mailto:me@florianreinhard.de) or create a [pull request](https://github.com/arewequantumyet/arewequantumyet.github.io).</span>
