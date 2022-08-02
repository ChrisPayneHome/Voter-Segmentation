# Voter-Segmentation


![pca_plot](https://user-images.githubusercontent.com/67926222/182265112-6d568359-6c21-4633-bd5b-3cbd60b8fb8b.png)



## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Rmarkdown & HTML](#markdown)
4. [HTML](#html)

## Introduction

A project using unsupervised machine learning to segment voters 

## Data

The data used for this project is the latest edition of the <a href="https://www.britishelectionstudy.com/data-object/wave-21-of-the-2014-2023-british-election-study-internet-panel/">British Election Study (BES) panel survey</a>. This data is stored as a Stata file (.dta) and to read into R you'll need to use functions from the haven package. Because of this, many of the fields in the data are labelled. As part of our data cleaning process we extract the labels from some of these fields and replace the values with these labels.

This project only used a small number of the variables as I felt it was the only fields that were necessary. Feel free to explore the data!

## Rmarkdown & HTML


