<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SPIKE-ENCODER-CHARACTERISER — repository foundation
-->

# Decision: separate encoder characterisation from encoding algorithms

## Context

Encoder choice requires matched continuous inputs, complete record populations, explicit representations and quality/cost methods. A spike count, single probe score or elapsed Python runtime alone cannot establish general information preservation or physical latency.

## Decision

Spike Encoder Characteriser owns admission, source adapters, complete sweep orchestration, independent reconstruction/probe analysis and comparable reports. It imports actual encoders from SC-NeuroCore. Common evidence and spike-log serialization come from separately installed owning providers; algorithms and wire semantics are not vendored or reinvented here.

## Consequences

Repository tooling can be qualified separately from the future characterisation runtime. Its qualification cannot stand for encoder, dataset, uncertainty or physical results. A source/interface change requires the actual adapter, consumer, native counterpart and affected reference tests before support is claimed. All seven software families remain in the intended population; the fabric extension keeps its separate actual measurement gate.
