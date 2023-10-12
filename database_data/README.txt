
CREATE TABLE Publishers (
    id INT,
    name VARCHAR(255),
    country VARCHAR(255)
);

CREATE TABLE Game (
    id INT,
    title VARCHAR(255),
    genre VARCHAR(255),
    release_date DATE,
    publisherID INT
);

CREATE TABLE Distributor (
    distributorID INT,
    name VARCHAR(255),
    website VARCHAR(255)
);

CREATE TABLE Inventory (
    gameID INT,
    distributorID INT,
    stock INT,
    price DECIMAL(10, 2)
);


