body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #fef9f4;
}

header {
    background-color: #ff6f61;
    color: white;
    text-align: center;
    padding: 20px 0;
}

.input-section {
    display: flex;
    justify-content: center;
    margin: 20px 0;
}

input {
    width: 300px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px 0 0 5px;
    outline: none;
}

button {
    padding: 10px 15px;
    border: none;
    background-color: #ff6f61;
    color: white;
    cursor: pointer;
    border-radius: 0 5px 5px 0;
}

button:hover {
    background-color: #e65b50;
}

.recipes-section {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.recipe-card {
    background: white;
    border-radius: 10px;
    padding: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    text-align: center;
}

.recipe-card img {
    width: 100%;
    border-radius: 10px;
}

.recipe-card h3 {
    margin: 10px 0;
}

.recipe-card a {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 12px;
    background-color: #ff6f61;
    color: white;
    border-radius: 5px;
    text-decoration: none;
}

.recipe-card a:hover {
    background-color: #e65b50;
}
