# Pokemon Go API Demo

 * USE AT YOUR OWN RISK !
 * includes protobuf file
 * ugly code

# Installation & Usage

 * requires python 2 (recommend `2.7.9`) and python package manager `pip`
 * create an account on [pokemon trainer club](https://sso.pokemon.com/sso/login?locale=en&service=https://www.pokemon.com/us/pokemon-trainer-club/caslogin) to use (in case account gets banned)
 * clone down repo, switch to `simulation` branch
 * `pip install -r requirements.txt` to install dependencies
 * to run the script: `main.py --debug -u POKEMON_TRAINER_USERNAME -p POKEMON_TRAINER_PASSWORD --location "1 King St, Toronto"`

## Demo

    $ python2 main.py --debug -u tejado -p 1234 --location "New York, Washington Square"
    [!] DEBUG mode on
    [!] Your given location: Washington Square, Greenwich, NY 12834, USA
    [!] lat/long/alt: 43.0909305 -73.4989367 0.0
    [!] login for: tejado
    [+] RPC Session Token: TGT-899360-gFKDueEjBcKX4G ...
    [+] Received API endpoint: https://pgorelease.nianticlabs.com/plfe/401/rpc
    [+] Login successful
    [+] Username: tejado
    [+] You are playing Pokemon Go since: 2016-07-13 08:10:20
    [+] Poke Storage: 250
    [+] Item Storage: 350
    [+] POKECOIN: 0
    [+] STARDUST: 600

## Credits
Thanks a lot to [Mila432](https://github.com/Mila432/Pokemon_Go_API) !  
[C# Port](https://github.com/BclEx/pokemongo-api-demo.net) by BclEx
