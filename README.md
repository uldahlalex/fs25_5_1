# WELCOME TO FULLSTACK!

<iframe width="560" height="315" src="https://www.youtube.com/embed/G5b1Zd367sA?si=RxfcLd0Zdc_pokbO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Agenda

- 08:15: Intro to WebSockets
- 08:45: Exercise A: First WebSocket API
- 09:30: Exercise A walkthrough in class
- 10:00: Exercise B + C

[//]: # (github repo link uldahlalex/fs25_5_1)
Today's remote repo is located [here](https://github.com/uldahlalex/fs25_5_1).

## Exercises

<details>
    <summary style="font-size: large">Exercise A: First WebSocket API (Stateless with "echo")</summary>

<div style="margin-left: 20px; box-shadow: 10px 10px 10px black;">

#### Task: 

Create a .NET WebSocket API with Fleck.
We aim to make the most basic WS server: "Stateless" (API doesn't retain data) and only "echos" client messages (gives back what it receives).

(img)

#### Instructions:
Install "Fleck" as Nuget to a .NET Web project.

You may follow the "Example" from the README.md here:
https://github.com/statianzo/Fleck

*Tip: Add some logic to "stall" the application after starting the server. Otherwise, it will just stop once the end of file is reached. You may use this snippet:*
```csharp
Console.ReadLine();
```

### Let's put it to use now!

We need a client to use the WS API now.

**First API usage: Use Postman Desktop's WebSocket Client:**

You can Download Postman Desktop client here (the browser version doesn't have WebSocket capability):

*Tip: You can download my Fullstack2025 Postman Collection. You can find prepared Websocket connections + messages in "fs_5_1"*

Upon success, you should be able to connect multiple clients and get an echo response from the API:

(img)

**Second API usage: Simple browser app using a single HTML file with JS** (observational exercise)

Use this file: (direct remote repo file link) with your web browser.
Now go to the network tab and inspect "WS" traffic. You should be able to see messages going both ways when chatting with the API.

</div>



###


</details>

<details>
    <summary style="font-size: large">Exercise B: WebSocket API with State + Broadcasting</summary>

<div style="margin-left: 20px; box-shadow: 10px 10px 10px black;">

#### Task: 

</div>
</details>


<details>
    <summary style="font-size: large">Exercise C: A Proper Client App For The API</summary>

<div style="margin-left: 20px; box-shadow: 10px 10px 10px black;">

#### Task: Instead of using Postman 

</div>
</details>



<details>
    <summary style="font-size: large">Food for thought</summary>

<div style="margin-left: 20px; box-shadow: 10px 10px 10px black;">

#### Questions

#### Additional literature & references

</div>
</details>

