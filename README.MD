## Just a simple script to display the weather on the terminal using the wttr API

**if no parameters are passed the the weather information will come for the user local ip** 

-l for specify a location

    $ bash weather -l Paris
    Weather for City: Paris, France

         \   /     Clear
          .-.      10 – 11 °C
       ― (   ) ―   ↑ 11 km/h
          `-’      10 km
         /   \     0.0 mm

-c flag for a complete report

```
$ bash weather -c tokyo
```

![Weather Report](https://i.imgur.com/11udjgM.png)

-r flag for a resumed one line report

```
$ bash weather -r
Nuremberg: 🌦 +11⁰C
```

**to avoid every time have to type bash and the script you can create a alias on the bashhrc or zshrc file**

```
alias weather="bash path-to-script/script"
```

to apply the new alias you can restart the session or souce the file

```
source ~/.bashrc or zshrc
```
