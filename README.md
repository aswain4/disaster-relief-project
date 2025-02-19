# Haiti Disaster Relief Image Classification Project
**Note: that this was a project for the Statistical Learning class I took as part of the Master's of Data Science program at UVA.**

## Project Overview
This project implements classification algorithms to solve a critical humanitarian challenge from the 2010 Haiti earthquake: locating displaced persons in need of emergency aid. Following the earthquake, displaced persons created temporary shelters using blue tarps. While rescue teams from the U.S. military needed to deliver food and water to these locations, the destruction of infrastructure and vast area made locating these shelters extremely challenging.

## Background
The Rochester Institute of Technology supported rescue efforts by collecting high-resolution geo-referenced imagery via aircraft. However, the volume of images collected daily made manual review impractical for timely aid delivery. This project explores data-mining algorithms as a solution for rapidly and accurately identifying blue tarps in aerial imagery to help direct rescue workers to displaced persons' locations.

## Technical Approach
The project evaluates multiple classification methods to:
- Process high-resolution aerial imagery
- Identify blue tarps indicating temporary shelters
- Assess algorithm performance using cross-validation
- Validate results against a hold-out testing set
- Compare methods based on accuracy and processing speed

## Project Goals
1. Implement and test multiple classification algorithms on the Haiti imagery dataset
2. Evaluate each method's effectiveness in identifying displaced persons' shelters
3. Optimize for both accuracy and speed to support time-critical humanitarian aid
4. Document and compare model performance through rigorous validation methods

## Data
The project uses actual aerial imagery data collected during the 2010 Haiti earthquake relief efforts. This includes:
- High-resolution geo-referenced imagery
- Labeled training data identifying blue tarp locations
- Hold-out testing set for final validation

## Significance
This project demonstrates the practical application of machine learning algorithms in humanitarian crisis response. By automating the identification of temporary shelters, we aim to support more efficient and effective delivery of emergency aid to displaced persons in disaster situations.
