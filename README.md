# 🌌 DeepFalcon GSoC 2025 – Graph Representation Learning for Fast Detector Simulation

This repository contains my submission for the [ML4SCI DeepFalcon GSoC 2025 project](https://github.com/ML4SCI/GSoC-DeepFalcon).  
The goal is to explore machine learning approaches for **fast detector simulation** using both **image** and **graph-based** representations of **quark/gluon jet events**.

---

## 🧠 Project Goals

### ✅ Common Task 1 – Variational Autoencoder (VAE)
Train a **VAE** on jet event images (ECAL, HCAL, Tracks) to learn a compressed latent representation and reconstruct the input images.

### ✅ Common Task 2 – Graph Classification with GNN
Convert jet images into **point clouds** and then **graph representations**. Use a **Graph Neural Network (GNN)** for **quark/gluon classification**.

### ✅ Specific Task 1 – Graph Autoencoder
Train a **Graph Autoencoder** to reconstruct node features of jet graphs. Evaluate and compare with the image-based VAE.

---

## 📂 Repository Structure

