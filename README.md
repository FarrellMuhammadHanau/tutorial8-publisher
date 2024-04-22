# Tutorial 8

1. How many data your publlsher program will send to the message broker in one run? <br>
    Terdapat 5 data yang publisher kirim yaitu
    - user_id = "1" dengan username = "2206081566-Amir"
    - user_id = "2" dengan username = "2206081566-Budi"
    - user_id = "3" dengan username = "2206081566-Cica"
    - user_id = "4" dengan username = "2206081566-Dira"
    - user_id = "5" dengan username = "2206081566-Emir"

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean? <br>
    Hal ini berarti publisher menggunakan server dengan hostname yang sama yaitu localhost dan port yang sama yaitu 5672, dan autentikasi dengan username yang sama yaitu guest dengan password yang sama yaitu guest

## Running RabbitMQ
![alt text](image1.png)

## Subscriber Console
![alt text](image2.png)

## Spikes
![alt text](image3.png)
Spikes ini terjadi ketika saya menjalankan publisher (saya menjalankan 3 kali dalam 1 menit) dan publisher akan mengirimkan 5 data dalam setiap run 