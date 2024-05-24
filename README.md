# DDos_attack
This project aims to detect Distributed Denial-of-Service (DDoS) attacks

This project aims to detect Distributed Denial-of-Service (DDoS) attacks using machine learning techniques And Deep Learning. The dataset used in this project contains network information with features such as date, switch, source, destination, packet count, byte count, duration of communication, and other relevant attributes. The dataset includes a total of 104,345 records, each labeled as either "normal" or "DDoS attack". The project demonstrates data processing, feature selection, and the implementation of a machine learning model to classify network traffic as normal or under a DDoS attack.

## Project Overview

This project demonstrates the use of machine learning techniques and Deep Learning to detect Distributed Denial-of-Service (DDoS) attacks in network traffic data. The dataset used contains various network attributes and is labeled to indicate normal traffic and DDoS attacks. The goal is to build a model that can accurately classify network traffic into these two categories.

## Dataset

The dataset used for this project is available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/shayalvaghasiya/ddos-sdn/data). It contains 104,345 records with the following features:

- **Date**: Timestamp of the record
- **Switch**: Switch identifier
- **Source**: Source IP address
- **Destination**: Destination IP address
- **Packet Count**: Number of packets transmitted
- **Byte Count**: Number of bytes transmitted
- **Duration**: Duration of the communication in seconds
- **Duration (nanoseconds)**: Duration of the communication in nanoseconds
- **Total Duration**: Total duration of the communication
- **Flows**: Number of flows
- **Packet Insertion**: Packet insertion rate
- **Packet per Flow**: Number of packets per flow
- **Byte per Flow**: Number of bytes per flow
- **Packet Rate**: Rate of packet transmission
- **Pair Flow**: Flow between pairs
- **Protocol**: Protocol used (e.g., TCP, UDP)
- **Port Number**: Port number used
- **Transmit Bytes**: Number of bytes transmitted
- **Receive Bytes**: Number of bytes received
- **Transmit Kbps**: Transmission rate in Kbps
- **Receive Kbps**: Reception rate in Kbps
- **Total Kbps**: Total data rate in Kbps
- **Label**: Target variable indicating whether the record is normal or a DDoS attack

## Installation

To run this project, you need to have Python installed along with the following packages:

- pandas
- numpy 
- seaborn
- matplotlib
- scikit-learn

You can install these packages using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
