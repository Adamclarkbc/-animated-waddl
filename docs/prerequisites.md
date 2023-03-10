# Prerequisites

## thundernetes foundational knowledge. π

Here you will find resources that will fill the knowledge gaps when working with technologies within thundernetes. 

π**thundernetes** was named after a combination of the words *thunderhead* and *kubernetes*. 
Thunderhead is the internal code name for the [Azure PlayFab Multiplayer Servers](https://azure.microsoft.com/services/playfab/multiplayer-services/) service. 

## Docker and Containerisation π’

- [Docker Basics](https://www.docker.com/101-tutorial)

## Kubernetes πΌ

Kubernetes is built on top of Docker to run containers at scale across many machines. We recommend that you have knowledge in the following Kubernetes areas before getting started with thundernetes.

### Kubernetes Resources 

- [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [Kubernetes core concepts for Azure Kubernetes Service (AKS)](https://docs.microsoft.com/azure/aks/concepts-clusters-workloads)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [kind](https://kind.sigs.k8s.io/)
  - kind is a tool for running local Kubernetes clusters using Docker container βnodesβ.
  - kind was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

## Game Servers πΎ

Thundernetes is a preview project from teams from Azure and XBox that enables you to run Linux game servers that use the PlayFab Game Server SDK (GSDK) on your Kubernetes cluster. 

- [Integrating Game Servers with Game Server SDK (GSDK)](https://docs.microsoft.com/gaming/playfab/features/multiplayer/servers/integrating-game-servers-with-gsdk)
- [Azure PlayFab Multiplayer Servers Gameserver Samples](https://github.com/PlayFab/MpsSamples)
- [PlayFab Game Server SDK](https://github.com/PlayFab/gsdk)

## Azure Account βοΈ

You can host you Kubernetes clusters in Azure. If you don't have an account you can create one for free.
- [Create your Azure Account](https://azure.microsoft.com/free/?WT.mc_id=A261C142F)

### Azure Blob Storage

- [Blob Storage Overview](https://docs.microsoft.com/azure/storage/blobs/storage-blobs-overview)

## Game Engine π?

Using your multiplayer game to intergrate with thundernetes.

- [Unreal Engine](https://www.unrealengine.com/)
- [Unity](https://unity.com/)

## Metrics πΉ

- [Prometheus Metrics](https://github.com/prometheus-operator/kube-prometheus)
