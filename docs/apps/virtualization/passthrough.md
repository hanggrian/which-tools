---
title: GPU passthrough
parent: Virtualization
nav_order: 2
---

# GPU passthrough
{: .no_toc }

&ldquo;One man’s crappy software is another man's full time job.&rdquo;
&mdash; *Jessica Gaston*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{: .warning }
> Specialized components are required for effective dual-GPU passthrough:
>
> - Motherboard with dual PCIe slots and IOMMU support.
> - Extra GPU for the guest OS, connected to a secondary monitor for HDR
    support.
> - Extra keyboard and mouse for the guest OS for minimal latency, KVM switch
    also works.

Passing through a GPU allows for gaming and other graphics-intensive tasks in a
virtual machine.

[PCI passthrough via OVMF](https://wiki.archlinux.org/title/PCI_passthrough_via_OVMF)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

## VM management

Work in progress.
