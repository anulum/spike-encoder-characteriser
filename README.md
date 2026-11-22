<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SPIKE-ENCODER-CHARACTERISER — repository foundation
-->

# Spike Encoder Characteriser

Spike Encoder Characteriser is being built to measure reconstruction quality, spike cost and latency for source-pinned sensor-to-spike encoders. This checkout contains repository validation tooling and documentation. Full foundation qualification is in progress. There is no installed characterisation package, executable encoder runner, public characterisation command or measured characterisation result.

Spike Encoder Characteriser is part of the **SC Neuromorphic Computing Systems** group (SC-NEUROMORPHIC-COMPUTING-SYSTEMS). The [group and project map](https://github.com/anulum/sc-neurocore/blob/main/docs/ecosystem.md) shows the whole programme and where this repository sits in it.

## Boundary

SC-NeuroCore owns encoder implementations. This project owns the planned continuous-stimulus registry, explicit adapters, complete grid runner, independent reconstruction and single-task-probe metrics, and comparable clouds and Pareto reports. Shared evidence operations belong to the separately installed Evidence Manifest Toolkit. Optional vendor conversion belongs to Spike Format Bridge.

The intended software population contains rate, latency, phase, burst, rank-order, delta and sigma-delta. Five functions accept buffered vectors and a model window; two consume complete time sequences and a threshold. Their output maps, sign loss, tie ordering and unsupported controls remain explicit. A separately gated fabric extension requires actual device and timing evidence. A model tick is not a physical clock measurement.

## Current tooling

Seven repository controls inspect metadata, source attribution, workflows, dependency alignment, native documentation, inventory and preflight orchestration. The selected native-tool bootstrap verifies development executable and licence bytes. The descriptor declares architecture-only maturity and empty implemented domain capability and claim inventories.

Use the exact development environment in [Contributing](CONTRIBUTING.md). Named entry points are make metadata, make source-provenance, make workflows, make dependencies, make docs, make inventory and make licence. Full CI/preflight belongs in CI or an explicitly admitted pre-push environment. See [Validation](VALIDATION.md) for scope and limits.

## Documentation and support

[Architecture](ARCHITECTURE.md), [support](SUPPORT.md), [security reporting](SECURITY.md) and [citation metadata](CITATION.cff) describe this checkout's scope. No hosted service, package release, DOI, public CI status, hardware timing or performance advantage is claimed.

## Licence

Source is licensed under [AGPL-3.0-or-later](LICENSE). A commercial licence is available through the contact in [NOTICE](NOTICE.md).

![ANULUM](docs/assets/anulum_logo_company.jpg)

![Fortis Studio](docs/assets/fortis_studio_logo.jpg)

## Text and data mining reservation
The rightsholder, Miroslav Šotek (ANULUM), expressly reserves the use of the
works in this repository for text and data mining, including the collection of
this content for, and its use in, training, fine-tuning or evaluating machine
learning and artificial intelligence models, in accordance with Article 4(3) of
Directive (EU) 2019/790 and the national provisions transposing it.

No permission for such use has been granted beyond what the licence in
`LICENSE` grants. This reservation does not change that licence: uses the
licence permits remain permitted on its terms, including its attribution and
share-alike conditions.

Reservation made on 2026-10-19. Requests for permission: contact the
rightsholder through the contact listed in this repository.
