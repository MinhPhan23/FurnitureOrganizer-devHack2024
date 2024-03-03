# Welcome to Furniture Organizer, devHack2024 project

## Introduction
This project was developed by Minh Phan, Amirhossein Mashghdoust and Min Kyu Jung for University of Manitoba's devHack2024.

Furniture Organizer is a simple application that tries to optimize furniture placement so that you can have maximum free space in your room.

What do we mean by **_free space_**? After all, the area of free space will never change no matter how you place the furniture.

We define **_free space_** as the maximum area of rectangle you can fit in the space.

This makes our project a variation of the [2D Packing Problem](https://en.wikipedia.org/wiki/Bin_packing_problem).

## How to run

1. Run `python3 manage.py runserver`
2. Visit `http://127.0.0.1:8000/`
3. In the Furniture Organizer interface, we have to upload a JSON file that contains the room size as well as the furniture size. Click on "Choose file" and upload the test JSON file called `~/dataStub/test1.json` or `~/dataStub/test2.json`. Then press "Upload"
4. Once uploaded, press "Visualize Input." This will visualizes both the room and furniture specified in the JSON file.
5. Click on "Optimize." This will place the first most optimal furniture in the room. Keep pressing "Optimize" until all furniture are placed.