# Social Media Protocol

## Introduction

The rapid growth of decentralized social networks has created a need for standardized protocols that enable seamless 
interactions between different platforms and applications. One crucial aspect of these interactions is the uploading and sharing of media content, such as images, videos, and audio files. To address this need, the Social Media Protocol (SMP) has been developed to define a common JSON structure and set of types for uploading media to InterPlanetary File System (IPFS) in a standardized way.

## Overview

SMP is an open standard that provides a unified framework for decentralized social networks to upload and share media content. The protocol defines a set of JSON schemas and data types that enable platforms and applications to seamlessly integrate with IPFS, a decentralized storage system. By using the SMP, developers can ensure interoperability between different platforms, enabling users to share media content across various decentralized social networks.

SMP consists of three primary components:

1. **Media Data**: A standardized JSON object that represents a single media item, such as an image or video.
2. **Metadata Object**: A JSON payload that encapsulates the Media Object and additional metadata, such as user authentication information and upload settings.
3. **Social Network Signature**: A JSON response that provides the IPFS content identifier (CID) and other relevant metadata about the uploaded media item.

By adopting the SMP, decentralized social networks can ensure seamless interactions, facilitate content sharing, and promote a more open and interoperable ecosystem for users.

## Making Improvement Requests and Contributing to the Open Protocol

SMP is an open protocol, and we encourage contributions from the community to improve and extend its capabilities. If you have a proposal for a new media or data structure type, or would like to suggest improvements to the existing standard, please follow these guidelines:

## Improvement Request Process

1. **Fork the Repository**: Create a fork of the official SMP GitHub repository.
2. **Create a New Branch**: Create a new branch in your forked repository for your proposed improvement.
3. **Write a SIP (Social Improvement Proposal)**: Write a clear and concise proposal that describes the problem, the solution, and the implementation details. The proposal should include:
	* A brief summary of the improvement
	* Motivation and background information
	* Technical specification of the proposed change
	* Examples or reference implementations
4. **Open a Pull Request**: Open a pull request to merge your branch into the official SMP repository.
5. **Discuss and Refine**: The SMP maintainers and community will discuss and refine your proposal.

## SIP (Social Improvement Proposal) Template

To facilitate the improvement request process, we provide a template for writing SIPs:

[SIP Number]

[Title]

[Summary]

[Motivation]

[Technical Specification]

[Examples or Reference Implementations]

Example:

```
SIP-5: Add Support for 3D Model Media Type

Title: Add Support for 3D Model Media Type
Summary: This SIP proposes the addition of a new media type for 3D models, enabling decentralized social networks to support immersive and interactive content.
Motivation: The growth of virtual and augmented reality technologies has created a need for standardized protocols that enable seamless interactions between different platforms and applications.
Technical Specification:
	* Media Object schema extension for 3D model metadata (e.g., format, dimensions, materials)
	* Upload Request payload modification to accommodate 3D model data
Examples or Reference Implementations: [Insert examples or reference implementations]
```

By contributing to SMP, you can help shape the future of decentralized social networks and enable a more open and interoperable ecosystem for users.
