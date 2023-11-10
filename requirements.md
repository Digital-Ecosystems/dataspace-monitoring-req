# Dataspace Monitoring as a Service
This document describes the requirements of the tool to monitor the dataspace deployment over the IONOS cloud from the cloud infrastructure as well as from the application instances perspective.

## 1. Source of data/measurements
Context: for monitoring data spaces based on the IONOS cloud resources and services as well as the dataspace application status (GXFS Catalogue, EDC)

### 1.1 Monitoring IONOS Cloud Resources
 - CloudAPI integration for retrieving info on how many resources are allocated to which applications: https://api.ionos.com/docs/cloud/v6/
 - S3 buckets: API link: 

### 1.2 Monitoring DNSaaS
- API: action point: contact the DNSaaService team

### 1.3 Monitoring the dataspace building blocks
- GXFS Catalogue: action point: contact the community
- EDC Instance Manager: Fraunhofer ISST - contact, open Telemetry
- EDC instances application layer status (healthiness)

### 1.4 Monitoring DBaaS
- API:

## 2. GUI
- Integration with Grafana (to be clarified)
- definition of Dashboard - mockups

## 3. Data storing
Req: compatible with future analysis modules: get info from Monitoring as a Service team

## 4. Analysis and Prediction (future)
- Manager of the deployment - enter envisoned scaling (from day X - consider normal to have 1 million users)
