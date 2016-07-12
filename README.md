

```html

<x:top white softbg imgroll="img/roll">
    <x:e logo>
        img.hakim.dark
    </x:e>
</x:top>

<x:main black>
    <x:txt title="We are the music makers.">
        A pirate utopia on the endless waves of the ever-expanding net, we stand at the edge of this world.  Through music, the zenith of our intelligence, the purest form of meaningless beauty, we offer both a refuge for wandering mind and a weapon with which to shatter the hoax of reason.
    </x:txt>
    <x:txt cap>
        The net is vast and infinite.
    </x:txt>
    <x:x for="m" in="music.albums">
        <x:track>
            <x:e>m.title</x:e>
            <x:e>m.artist</x:e>
            <x:e>m.description</x:e>
            <x:e img>m.img</x:e>
            <x:e sound>m.wave</x:e>
        </x:track>
    </x:x>
</x:main>

```