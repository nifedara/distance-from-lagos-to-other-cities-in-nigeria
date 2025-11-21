# Distance from Lagos to other cities in Nigeria

## About
Uses `Geopy` to calculate the geodesic distance between coordinates
- Data: `worldcities` data (Basic) https://simplemaps.com/data/world-cities
- Notebook to recreate: [calculate distance between coordinates](https://github.com/nifedara/distance-from-lagos-to-other-cities-in-nigeria/blob/main/the_distance_from_Lagos_to_cities_in_Nigeria.ipynb) or [this](https://github.com/nifedara/distance-from-lagos-to-other-cities-in-nigeria/blob/main/calculate_distance_btw_coordinates.ipynb). One uses csv-DictReader to read the file, the other uses `pandas`

## Preview  
<img width="623" height="900" alt="image" src="https://github.com/user-attachments/assets/c385f363-68d8-424e-8b45-0b127c6fb7be" />

## Installation 🔨
Using `conda` from your Command prompt/Anaconda prompt

1. Create an environment for your installation:

```
conda create --name calculate_distance
```

2. Activate the environment:
```
conda activate calculate_distance
```

3. Install required packages:

```
conda install --channel conda-forge geopy jupyter-lab -y
```

4. Run JupyterLab:
```
jupyter-lab
```
