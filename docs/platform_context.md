# Platform Context

## Private Host

SIS is one workflow inside a private Synthetic OS Labs application host. The host also supports Carter and EAS, but this repository documents only SIS.

## Access

The implemented workflow requires authorized scientist access before the SIS interface is available.

## Carter Relationship

SIS uses Carter as the underlying execution runtime. Carter handles governed generation, asynchronous job execution, and result handling. SIS supplies the structured invention-vector prompt assembled from the Scientist Input Module.

## What Is Not Included

This public repository does not describe login implementation, session logic, route names, provider details, storage layout, private Carter internals, EAS internals, deployment configuration, or operational logs.
