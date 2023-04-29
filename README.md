Prompt Engineering. This prompt book will help you learn essential building blocks and
all the techniques to master Stable Diffusion.
The secret for generating good images
A well-written prompt consisting of modiﬁers and a good
sentence structure. We will also show you all types of modiﬁers and some magic words.
Well-adjusted Stable Diffusion weights. You can
always use the default, but sometimes ﬁne-tuned weights can generate better results.
This will strengthen your ability to
bring your creative dream images to life.


Prompt keyword weighting is supported. You can increase the attention of a keyword but not higher than 1.5. 
Use the format (example:weight). By default, words have a coefficient of 1 (example: 0.4), they will have a lower priority.

Attention for words Technique:
Adding "()" in the prompt increases attention to enclosed words, while "[]" decreases it. You can combine multiple modifiers: 
- a (word) - increase attention to word by a factor of 1.1
- a ((word)) - increase attention to word by a factor of 1.21 (= 1.1 * 1.1)
- a [word] - decrease attention to word by a factor of 1.1
- a (word:1.5) - increase attention to word by a factor of 1.5
- a (word:0.25) - decrease attention to word by a factor of 4 (= 1 / 0.25)

You can also use a few words in "()" and "[]". You can also use a few words in "()" and "[]".

Also you can still use this structure: (example, example :weight), so the weight will increase for several words at once.
Examples: (grayscale, woodcut:1.2); (((blue hair, floating hair, liquid hair, chromatic aberration))); (rutkowski, artstation:0.8); (masterpiece, best quality:1.4); [cute, volumetric fog]

Please note that to increase or decrease the weight of several words, you need to put a comma between them.

Start by asking a list of questions
1. Do you want a photo or a painting?
2. What’s the subject of the photo? Person? An animal or perhaps a landscape?
3. What details do you want to add?
a) Special Lighting. Soft, ambient, ring light, neon

b) Environment. Indoor, outdoor, underwater, in space

c) Color Scheme. Vibrant, dark, pastel

e) Point of view. Front, Overhead, Side

f) Background. Solid color, nebula, forest

4. In a specific art style? 3D render, studio ghibli, movie poster
5. A specific photo type? Macro, telephoto

This is not an all-inclusive list, but will help you get great results when you start.
your prompt crafting journey.
                                                                                                                               
Answer the following questions:
1. Do you want a photo or a painting? => painting
2. What’s the subject of the photo? Person. animal, landscape. => a goldendoodle
3. In a certain camera position? side view, from bottom, from above, from behind => from behind
4. What details do you want to be added? => suit

a. Special Lighting. Soft, ambient, ring light, neon => natural light

b. Environment. Indoor, outdoor, underwater, in space => in the sky

c. Color Scheme. Vibrant, dark, pastel => with bright colors

5. In specific art style? 3D render, studio ghibli, movie poster => by Studio Ghibli

The order of words is important
The order and presentation of our desired output is almost as an important aspect as the vocabulary itself. It is recommended to list your concepts explicitly and separately than trying to cramp it into one simple sentence.

The keyword categories are:

1. Subject: what you want to see in the image, such as a person, an object, a scene, etc.
2. Medium: the material used to make the artwork, such as illustration, oil painting, realistic, anime, 3D rendering, etc.
3. Style: the artistic style of the image, such as impressionist, surrealist, pop art, etc.
4. Artist: the name of a specific artist or multiple artists whose style you want to emulate or blend.
5. Website: the name of a niche graphic website that aggregates images of a certain genre, such as Artstation or Deviant Art.
6. Additional details: any other modifiers that can enhance the image, such as sci-fi, stunningly beautiful, dystopian, etc.
7. Color: the overall color or tone of the image, such as iridescent gold, pastel pink, etc.
8. Lighting: the effect of light and shadow on the image, such as cinematic lighting, soft lighting, dark, dark shot,  bright, etc.

You don’t have to include keywords from all categories. You can use them as a checklist to remind you what could be used. 
 
 
 
Here are completely universal styles that you can combine and use in your prompt(I highly recommend using them!):

Keywords for natural skin: (natural skin texture: 1.2), (hyperrealism:1.2), (soft light:1.2), (sharp:1.2)

Keywords for gloomy style: complex background, stuff in the background, highly detailed, (gloomy:1.3), dark, dimmed, hdr, vignette, grimy, (slate atmosphere:0.8)

Keywords for horror cinematic style: slate atmosphere, cinematic, dimmed colors, dark shot, muted colors, film grainy, lut, spooky

Keywords for Cinematic art style: art by greg rutkowski, art by artgerm, soft cinematic light, adobe lightroom, photolab, hdr, intricate, highly detailed, (depth of field:1.4)

Keywords for Professional photo: (dark shot:1.4), 80mm,  soft light, sharp, exposure blend, medium shot, bokeh, (hdr:1.4), high contrast, (cinematic, teal and orange:0.85), (muted colors, dim colors, soothing tones:1.3), low saturation, (hyperdetailed:1.2), (noir:0.4)

Keywords for Engraving style: (grayscale, woodcut:1.2), (etching:1.1), (engraving:0.2), detailed

Keywords for Painting: rutkowski, intricate digital art, soothing tones, (cartoon:0.3), (art:1.4), epic realistic, faded, neutral colors, (hdr:1.4), (muted colors:1.4), (intricate), (artstation:1.5), dramatic, intricate details, (technicolor:0.9), detailed, intricate, cinematic, detailed
 
 
examples of works: 

realistic prompt: RAW photo, girl, 22 years old, upper body, selfie in a car, blue hoodie,(1girl), (realistic), (photo-realistic:1.5), inside a car, driving, lipstick, freckles, (short hair), multicolor hair, necklace, (RAW photo, 8k uhd, film grain), Sharp Eyeliner, Blush Eyeshadow With Thick Eyelashes, extremely delicate and beautiful, 8k, soft lighting, high quality, highres, sharp focus, extremely detailed, during the day, (sunlight on face), beautiful detailed eyes, extremely detailed eyes and face, masterpiece, cinematic lighting, (high detailed skin:1.2), 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3

realistic prompt: fashion photography portrait of blue human avatar, in blue lush jungle with flowers and birds, 3d render, cgi, symetrical, octane render, 35mm, bokeh, (intricate details:1.12), hdr, (intricate details, hyperdetailed:1.15), (natural skin texture, hyperrealism, soft light, sharp:1.2)

realistic prompt: foxie european woman, ginger hair, winter forest, natural skin texture, 24mm, 4k textures, soft cinematic light, adobe lightroom, photolab, hdr, intricate, elegant, highly detailed, sharp focus, ((((cinematic look)))), soothing tones, insane details, intricate details, hyperdetailed, low contrast, soft cinematic light, dim colors, exposure blend, hdr, faded

realistic prompt: photo of coastline, rocks, storm weather, wind, waves, lightning, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3

realistic prompt: epic realistic, girl in military uniform, fast tense pose, model face, (intricate details:1.12), hdr, (intricate details, hyperdetailed:1.15), (dark shot:1.22), neutral colors, (hdr:1.4), (muted colors:1.4), (intricate), (artstation:1.2), hyperdetailed, dramatic, intricate details, (technicolor:0.9), (rutkowski:0.8), cinematic, detailed

realistic prompt: a young woman, street smiling, backpack, ponytails, epic realistic, photo, faded, complex stuff around, intricate background, soaking wet, neutral colors, ((((hdr)))), ((((muted colors)))), intricate scene, artstation, intricate details, vignette

realistic prompt: cinematic shot, centered, cinematography, intricately detailed, crafted, meticulous, magnificent, maximum details, extremely hyper aesthetic, realistic, (((1girl, solo))), 18age, short hair, black hair, (((center))), nurse uniform, nude

realistic prompt: (extremely detailed CG unity 8k wallpaper), (masterpiece), (best quality), (ultra-detailed), (best illustration), (best shadow), ultra-high res, (realistic, photo-realistic:1.2), 1girl, shopping mall rooftop cafe, white opaque shirt with bow tie, puffy eyes, looking at viewer, smile, close up

realistic prompt: (masterpiece, best quality:1.4), realistic, photorealistic, 1girl, solo, female paladin, young woman, [cute], stunningly beautiful, medium breast, slender, vambraces, (intricate full plate armor, no helmet:1.2), medium blonde hair, highly detailed eyes, soft eyes, realistic pupils, lace trimmed hairband, (curly hair:1.4), (parted bangs:1.3), full lips, (close up), (embarrassed, ashamed:1.3), gauntlets, cape, (sweatdrop:1.3), freckles, (looking at viewer:1.2), highly detailed skin, skin pores, subsurface scattering, fantasy, stone wall background, large stones, absurdres, perfect anatomy, realistic proportions, perfect lighting, sharp focus, 85mm lens, side lighting, vibrant, film still, photographed by Canan EOS R6, 135mm, 1/1250s, f/2.8, ISO 400

realistic prompt: end of the world, epic realistic, (hdr:1.4), (muted colors:1.4), apocalypse, freezing, abandoned, neutral colors, night, screen space refractions, (intricate details), (intricate details, hyperdetailed:1.2), artstation, cinematic shot, vignette, complex background, buildings, snowy

realistic prompt: alluring stuning gorgeous posing european drunk homeless sexy business lady weared ((dirty)) ripped skirt, ripped blouse, intricate enviroment, intricate texture of skin, food waste, trash, garbage, little dead rat , night, night street lights, carton boxes, cute face, sexual intention, normal legs

realistic prompt: portrait of a Ukrainian woman, ( detailed grain skin:1.3), scarf around the neck, (mole), (she bit her lower lip:1.3), Bob haircut, (messy hair:1.4), gray eyes, (tears in his eyes), (glossy eyes:1.1), adobe lightroom, photolab, hdr, 50mm camera, studio lighting, professional, (colorful background:1.3)

realistic prompt: (8k, best quality, masterpiece:1.2),(best quality:1.0), (ultra highres:1.0), watercolor, a beautiful woman, shoulder, hair ribbons, by agnes cecile, full body portrait, extremely luminous bright design, (pastel colors), forest background, modelshoot style, very long hair, intricate, elegant, realism, (hyperrealism), (cinematic), (hyperdetailed:1.2), hdr

realistic prompt: highest quality, award-winning, professional erotic photo of (sexy pale woman rancher with beautiful blonde hair), ((pretty face)), seductive look, (wearing cowgirl outfit, daisy dukes), athletic body, small breasts, large ass, candid, (breast worship:0.7), (detailed skin), [beauty marks], freckles, hyperrealistic photography, outdoors, standing in front of old western tavern, (storm clouds in the sky above), stormy weather, natural lighting, (crepuscular rays:0.6), photographed on a Sony a9 II Mirrorless Camera , 50mm prime lens, F/1.4, (highly detailed), cinestill 800, 8mm film grain, dynamic angle, full body, cowboy shot

realistic prompt: Cinematic film still, full body, of ((Norse Female serpent goddess)), (Hel), pale skin, (Lying on her back in a pit of snakes)), legs spread, toned abs, large breasts, seductive look, exposed pussy, large ass, ((tentacle sex)), ((detailed facial features)), alluring blue eyes, (wet, detailed skin), (covered in snakes), blonde hair, magic, (dark cave:1.2), (cold colors), damp, moist, intricate details, shallow depth of field, [volumetric fog], cinematic lighting, reflections, photographed on a Canon EOS R5, 50mm lens, F/2.8, HDR, 8k resolution, cinematic film still from Vikings

realistic prompt: nude brunette girl with round frame glasses, thin lips, slender body, young face, (glasses are refractive with chromatic aberration), messy hair, posing on bed with white sheets, full body photo, bright room, window, sunlight, white sunbeams, 4k, realistic, ultra detailed, detailed, masterpiece, highres, by Jeremy Lipking, by Antonio J Manzanedo, (by Alphonse Mucha:0.5) ((Ultra detailed))

realistic prompt: Highly detailed cinematic film still, Hip level shot, of (fit female soldier, wearing high-tech black Exo suit, helmet), running through the jungle, (lush vegetation), (mountains:1.1), (god rays:0.4), dense alien jungle, toned body, (highly detailed, hyperdetailed, intricate), (lens flare:0.4), (bloom:0.5), particle effects, cinematic lighting, (soft lighting:0.6), prominent projected shadows, deep depth of field, (film grain:0.5), photographed on a Leica SL (Typ 601) Mirrorless Digital Camera, 50mm wide angle lens, F2.8 aperture, deep focus, (RAW), cinematic film still from Gravity 2013

realistic prompt: Highly detailed RAW color Photo, Rear Angle, Full Body, of (female space soldier, wearing vivid dark red and white space suit, helmet, tined face shield, rebreather, accentuated booty), outdoors, (looking up at advanced alien structure), toned body, big butt, (sci-fi), (mountains:1.1), (lush green vegetation), (two moons in sky:0.8), (highly detailed, hyperdetailed, intricate), (lens flare:0.7), (bloom:0.7), particle effects, raytracing, cinematic lighting, shallow depth of field, photographed on a Sony a9 II, 50mm wide angle lens, sharp focus, cinematic film still from Gravity 2013, (NSFW)

realistic prompt: postapocalypse, High detail RAW color Photo, closeup shot, of (rebellious Polish woman, wearing Slavic attire, military Cossack Ushanka), (sitting on couch in (Atompunk) soviet union living room), (Cyrillic tattoos), (elegant, beautiful face), (retrofuturism), mechanical, gears, (detailed skin), (oil:0.6), (tesla coil:0.4), (Nixie tube:0.8), (highly detailed, hyperdetailed, intricate), (bloom:0.4), soft lighting, (side lighting:0.8), shadow casting, deep focus, photographed on a Leica 10772 M-P, 85mm macro lens, F/8 aperture, film still, (Cursed soldiers, rebellion)

realistic prompt: (level difference:1.8),(Paint colliding and splashing on the canvas),(depth of field), 1girl's side face blends into it, ((side face)), open mouth, (liquid paint rainbow hair:1.1), made of paint and defies gravity,thick flowing, (paint splatter:1.3), Liquid state, stunningly beautiful, masterpiece, detailed background, ultra high quality model, ethereal background, abstract beauty, explosive volumetric, oil painting, heavy strokes, Romantic lighting, Sub-Surface Scatterring, lens 135mm, f1.8, glow, 8k, high resolution, dreamy, ray tracing, hdr, god rays

realistic prompt: shukezouma, octane render, hdr, (hyperdetailed:1.15), (soft light, sharp:1.2), 1girl, beautiful girl, ultra detailed eyes, mature, plump, thick, rainbow painting drops, paint teardrops, woman made up from paint, entirely paint, splat, splash, long colored hair, kimono made from paint, ultra detailed texture kimono, rainbow paint kimono, paint bulb, paint drops, (hair ornaments, earrings, flowers hair ornaments, butterflies hair ornaments), outdoors, sakura trees

realistic prompt: (Cinematic photo: 1. 3), portrait of a vampire cat dressed as a count, ((full body)) directional look, cinematic composition, (intricately detailed, fine details, hyperdetailed), ultra-detailed, (backlight:1. 2) intricate, style-empire

realistic prompt: (photorealistic:1.4), official art, unity 8k wallpaper, ultra detailed, beautiful and aesthetic, masterpiece, best quality, (zentangle, mandala, tangle, entangle), tattoo, 1girl, extremely detailed, nude, large breast, full body, dynamic angle, the most beautiful form of chaos, elegant, a brutalist designed, vivid colours, romanticism, by james jean, roby dwi antono, ross tran, francis bacon, michal mraz, adrian ghenie, petra cortright, gerhard richter, takato yamamoto, ashley wood, atmospheric, ecstasy of light and shadow, deep shadow, low key

realistic prompt: Margot Robbie, malice, skulls, tendrils, dark atmosphere, greyscale, detailed linework, cinematic, psychedelic, black paper with vibrant turqoise line work, ornate, symmetrical, tarot card, highly detailed, ink illustration, style of peter mohrbacher, golden ratio


just an example: drunk, creepy santa, muddy, crowded bottles bar, intricate details, hdr, intricate details, hyperdetailed, cinematic, dark shot, muted colors, film grainy, soothing tones, muted colors, technicolor

just an example: (masterpiece, best quality), (best illumination, an extremely delicate and beautiful), (best illumination, an extremely delicate and beautiful), (beautiful detailed face), (finely detailed eyes and detailed face:1.4), dark fantasy, (young girl, small beasts, 1girl, solo, crazy smile, pale skin, white hair, red glowing eyes, dynamic angle, vampire), (gaint vampire castle in background), (red moon, red sky), pointy ears, fangs, demon wings, demon horns, blood on face, blood rain, blood fog, (depth of field), high contrast, (blood splatter:1.4), full body

just an example: masterpiece, chinese dragon, long dragon, Loong,fangs,fantasy, mythical, art by( greg rutkowski:0.8), epic lighting, (photo realism:1.2), high quality, highly detailed, masterpiece, epic

just an example: epic video game key visual, giant armored creature, horde, skeletal army, many approaching in an ancient desert windy dust debris storm landscape midnight moonlight foreground debris (zrpgstyle) (masterpiece:1.2) (illustration:1.1) (best quality:1.2) (detailed) (intricate) (8k) (HDR) (wallpaper) (cinematic lighting) (sharp focus)

just an example: 1girl, beautiful vintage color, instagram (photorealistic, high resolution:1.4), ((puffy eyes)), looking at viewer, full body (8k, RAW photo, best quality, masterpiece:1.2), (realistic, photo-realistic:1.37),(sharp focus:1.2), professional lighting, photon mapping, radiosity, physically-based rendering, (pale skin:1.2),nsfw, small breasts,nipples, looking at viewer, middle hair, portrait, purple eyes, wet clothes(sliver hair:1.1),bangs, (simple background:1.4), solo, upper body, white background,realistic, (masterpiece:1.4), (best quality:1.4),(shiny skin), makeup, red lips, smile, (skinny,closed mouth,shy:1.3), blackshirt short sleeve, black pencil short skirt,black tight skirt, school unifrom

just an example: complex 3d render, ultra detailed, beautiful death angel, biomechanical cyborg, analog 150 mm lens, beautiful natural soft rim light, crystal feathers, roots, fine foliage lace, colorful details, Boris Bidjan Saberi outfit, pearl earrings, piercing, art nouveau fashion embroidered, intricate details, mesh wire, mandelbrot fractal, facial muscles, cable wires, microchip, badass, hyper realistic, ultra detailed, octane render, volumetric lighting, 8k post-production, red and white with a bit of black, detailled metalic bones, semi human, iridescent colors, Glenn Brown style, futuristic room, power of the god, high-angle shot, complex body poses

just an example: the anatomy of a head of lettuce, an ultrafine detailed painting by james jean, behance contest winner, vanitas, angular, altermodern

just an example: (RAW photo, best quality), (realistic, photo-realistic:1.3), masterpiece, an extremely delicate and beautiful, extremely detailed, CG, unity , 2k wallpaper, Amazing, finely detail, light smile, extremely detailed CG unity 8k wallpaper, huge filesize, ultra-detailed, highres, absurdres, soft light, (((medium hair:1.3), short bang, pink hair, floating hair novafrogstyle)), beautiful detailed girl, detailed fingers, extremely detailed eyes and face, beautiful detailed nose, beautiful detailed eyes, long eyelashes, light on face, looking at viewer, (closed mouth:1.2), 1girl, cute, young, mature face, (full body:1.3), ((small breasts)), realistic face, realistic body, beautiful detailed thigh, business suit, cross-laced clothes, collared shirt, open clothes, in office, detailed office, open cardigan, black thighhighs, miniskirt, black underwear, unbuttoned shirt

just an example: end of the world, epic realistic, (hdr:1.4), (muted colors:1.4), apocalypse, freezing, abandoned, neutral colors, night, screen space refractions, (intricate details), (intricate details, hyperdetailed:1.2), artstation, cinematic shot, vignette, complex background, buildings, snowy


anime prompt: (flat color:1.1),(colorful:1.3),(masterpiece:1.2), best quality, masterpiece, original, extremely detailed wallpaper, looking at viewer,1girl,solo,floating colorful water

anime prompt: (masterpiece, best quality, ultra-detailed, best shadow), (detailed background,dark fantasy), (beautiful detailed face), high contrast, (best illumination, an extremely delicate and beautiful), ((cinematic light)), colorful, hyper detail, dramatic light, intricate details, (1girl, solo,black hair, sharp face,low twintails, red eyes, hair between eyes,dynamic angle), blood splatter, swirling black light around the character, depth of field, black light particles, (broken glass), magic circle

anime prompt: (masterpiece, top quality, best quality, official art, beautiful and aesthetic:1.2), (1girl), extreme detailed, (fractal art:1.5),(cherry flowers in fractal art:1.3), colorful, highest detailed, upper body, purple hair, purple eyes, large breasts, kimono, bangs, sash, mole, obi, tassel, blush, hair ornament

anime prompt: (Girlish Painting:1.3), (Ultra detailed:1.3), (Cosy:1.3), best quality, masterpiece, highly detailed, ultra-detailed, 1girl, Emma Watson, unreal engin 5, octane render, (2D:1.2), limited palette flat color, digital painting, artstation, concept art, smooth, sharp focus, art by ross tran, art by greg rutkowski, art by alphonse Mucha, art by Bak Karol, (oil painting:1.16), (acrylic paint:1.16), (colorful:1.5), (watercolor:1.16), by nvinkpunk, kuvshinov, dreamlikeart, samdoesart, modelshoot style, (by Artist Koho Shoda:1.3), (by Artist Mike Mignola:1.3), (by Artist Joop Polder:1.3), (Classicism Art:1.3), (Industrial Art:1.3), (Solarpunk Art:1.3)

anime prompt: ((masterpiece, best quality)), 1girl, solo, flat chest, chain, cuffs, shackles, broken chain, collar, chained, handcuffs, barefoot, black and white hair, long hair, metal collar, solo, ankle cuffs, broken, purple eyes, very long hair, ball and chain restraint, bound, bdsm

anime prompt: (Highest picture quality), (Master's work), (ultra-detailed), (Detailed eye description:1.2), masterpiece, best quality, absurdres, original, extremely delicate and beautiful, beautiful detailed eyes and face, 1girl, black hair, cherry blossom, white clothes, looking at viewer, mole, pink flower, solo, (masterpiece:1.4), (best quality:1.4)

anime prompt: masterpiece, best quality, best detail, 5girls, swimsuit, focus on character detail, character on the front camera, high detail background, bloom, blue sky, high lighting detail, widescreen, 16:9, sea, beach, sunny day, medium hair, red face, megane, smile, sexy pose, realistic finger detail, close-up, portrait, getting wet, random hair colors, standing, erotic, yuri, hentai, nipple, leg strap, sexy hip, see-through, Draw realistic hand, random eye color, erotic face, sexy eye contact, half-naked, random hairstyle, random face, hold breast pussy, megane, pussy cum, small breast, yuri sex, kissing, open mouth, tongue, breasts grab

anime prompt: masterpiece, high quality, highres, absurdres, ultra-detailed, detailed eyes, 8k, 1girl, colorful eyes, fangs, open mouth, blue eyes, bangs, colorful background, (graffiti mural walls background), looking at viewer, vibrant, contrast, blue hair, white hair, gradient hair, happy, high five, heart symbols

anime prompt:  (extremely delicate and beautiful:1.2),1girl,fashi-girl, bangs, blue eyes, blurry, blurry background, bow, brown hair, closed mouth, from side, hair between eyes, hair bow, lantern, light particles, long sleeves, looking at viewer, medium hair, night, red bow, solo, star symbol, upper body,smile,red lips

anime prompt: masterpiece, best quality, ultra-detailed, illustration, 1girl, solo, outdoors, camping, night, mountains, nature, stars, moon, tent, twin ponytails, green eyes, cheerful, happy, backpack, sleeping bag, camping stove, water bottle, mountain boots, gloves, sweater, hat, flashlight, forest, rocks, river, wood, smoke, shadows, contrast, clear sky, constellations, Milky Way, peaceful, serene, quiet, tranquil, remote, secluded, adventurous, exploration, escape, independence, survival, resourcefulness, challenge, perseverance, stamina, endurance, observation, intuition, adaptability, creativity, imagination, artistry, inspiration, beauty, awe, wonder, gratitude, appreciation, relaxation, enjoyment, rejuvenation, mindfulness, awareness, connection, harmony, balance, texture, detail, realism, depth, perspective, composition, color, light, shadow, reflection, refraction, tone, contrast, foreground, middle ground, background, naturalistic, figurative, representational, impressionistic, expressionistic, abstract, innovative, experimental, unique

anime prompt: best quality, masterpiece, high definition, high quality, high resolution, sharp focus, trending on Artstation, 4k, beautiful fantasy spring sunny scenery landscape, celestial japanese temple alone at the peak of a mountain overlooking the landscape below, high point of view

anime prompt: (flat color:1.1), (colorful:1.3), (masterpiece:1.2), best quality, masterpiece, original, extremely detailed wallpaper, looking at viewer,1girl,solo,floating colorful water

anime prompt: (masterpiece:1.2), (best quality:1.1), 1girl, transparent, perfect face, black silk stockings, high quality, cute, black hair, highest quality, ultra-detailed, extremely detailed, hyper detail, (intricate detail:1.2), (panties over black pantyhose:1.2), (Japanese sailor suit:1.2), (cameltoe:1.2), (lift feet:1.4), soles, lie down, park, looking at viewer, sun shine

anime prompt: (masterpiece, best quality:1.1), bird's eye view, asymmetrical, blue ocean, low tide, sea waves, coastal road, sandy beach, piers, sailboats, yachts, ship wake, contrail, cars, tourists, lighthouse, seagulls, horizon, breeze, summer, morning, sunny, cloud, calm, fresh air, depth of field

anime prompt: masterpiece, best quality, ultra-detailed, illustration, 1girl, solo, fantasy, flying, broom, night sky, outdoors, magic, spells, moon, stars, clouds, wind, hair, cape, hat, boots, broomstick, glowing, mysterious, enchanting, whimsical, playful, adventurous, freedom, wonder, imagination, determination, skill, speed, movement, energy, realism, naturalistic, figurative, representational, beauty, fantasy culture, mythology, fairy tales, folklore, legends, witches, wizards, magical creatures, fantasy worlds, composition, scale, foreground, middle ground, background, perspective, light, color, texture, detail, beauty, wonder

anime prompt: masterpiece, best quality, 1girl, (colorful),(finely detailed beautiful eyes and detailed face),cinematic lighting,bust shot,extremely detailed CG unity 8k wallpaper, white hair, solo, smile, intricate skirt, ((flying petal)), (Flowery meadow) sky, cloudy sky, building, moonlight, moon, night, (dark theme:1.3), light, fantasy

anime prompt: masterpiece, best quality, ultra-detailed, illustration,2girls,fantasy, RPG, heroine, devil, final battle, outdoors, epic, dramatic, intense, powerful, dynamic, magic, spells, sword, shield, armor, wings, horns, tail, fire, smoke, light, shadow, impact, movement, energy, determination, bravery, courage, heroism, villainy, evil, darkness, destruction, victory, defeat, redemption, justice, sacrifice, friendship, companionship, teamwork, perseverance, challenge, obstacle, success, achievement, goal-oriented, progress, improvement, realism, naturalistic, figurative, representational, video game culture, anime, manga, Japanese, RPG tropes, character design, animation, special effects, composition, scale, foreground, middle ground, background, perspective, light, color, texture, detail, beauty, wonder

anime prompt: masterpiece, best quality, ultra-detailed, city, street, gothic, steampunk, illustration, 1girl, (solo), platinum long hair, boots, from behind, vintage, antique, brass, metal, gears, machinery, ornate, elegant, classic, sophisticated, refined, poised, contemplative, thoughtful, curious, mysterious, enigmatic, magical, watchful, intelligent, bookish, contrast, perspective, depth, texture, detail, realism, impressionistic, expressionistic, abstract, surrealistic, innovative, experimental, unique, atmosphere, ambiance, mood, nostalgia, historical, cultural, technological, industrial, fantasy, imagination, creativity, artistry, craftsmanship, skill, precision, detail, composition, balance, harmony, rhythm, colorful, darker, reflection, refraction, foreground, middle ground, background, vanishing point, horizon line, focal point, naturalistic, figurative, representational

anime prompt: (masterpiece, best quality:1.2), cinematic anime, anime clip of a 3 girls floating in space, universe, milky way, cosmos, planet, stars, astronaut, full body, ultra detailed, beautiful face, finely detailed eyes, extremely detailed, correct anatomy, incredibly_absurdres

anime prompt: ((masterpiece)), (((gray eyes))), (((blue hair, floating hair, liquid hair, chromatic aberration))), (focus on eyes, shaded, photo, insanely detailed, bloom:1.5), short hair, (photorealistic, masterpiece, dynamic angle, highest quality, (photorealistic, masterpiece, dynamic angle, highest quality, intricate, Alessandro Casagrande, Greg Rutkowski, Sally Mann, athletic wet punk body, (blue panties), nipples, concept art, 4k, far-off), (medium breasts, portrait, choker, soft), (sadness), (((blue flowers))), (((Night))), high sharpness, extreme saturation and contrast

anime prompt: ((4k,masterpiece, best quality)), shuimobysim, traditional chinese ink painting, lotus, hanfu, maxiskit, 1girl, solo, white hair, long hair, fox ears, white, bikini, fish, many fish near girl, look at viewer, tease

anime prompt: 1girl, ((cinematic light)), colorful, hyper detail, dramatic light, intricate details, best quality, (extremely detailed CG unity 8k wallpaper, masterpiece, best quality, ultra-detailed, best shadow), (detailed background:1.4), (beautiful detailed face, beautiful detailed eyes), High contrast, (best illumination, an extremely delicate and beautiful), (girl:1.5), solo, black skirt, blue eyes, electric guitar, guitar, headphones, holding, holding plectrum, instrument, long hair, music, one side up, pink hair, playing guiter, pleated skirt, black shirt, indoors ((caustic)), dynamic angle, beautiful detailed glow, full body, cowboy shot



About Modiﬁers

Modiﬁers are words that can change the style, format, or perspective of the image. There are certain magic words or phrases that are proven to boost the quality of the image. In this section, we will talk different types of modiﬁers you can use in your prompt.

Photography

Photography Prompt - Mix and Match!

Shot type- Close-up; Extreme Close-up; POV; Medium shot; Long shot; At a distance;
Style- polaroid; Tilt-shift; Color splash; Monochrome; white and black
Subject- Woman; Old man; Grey cat; Bunny; Ferrari;
Lighting- Cinematic light; Sun light; Ambient light; Soft light; moonlight; dramatic light
Context- Indoor; Outdoor; At night; In the park; Studio;
Lens- Wide-angle; Telephoto; 24mm; EF 70mm; Bokeh; F/1.4; 50mm
Device-iPhone X; CCTV; Nikon Z FX; Canon; Gopro; Fujifilm XT3 

Photography Styles

Polaroid -child,  sitting, wide empty city street, in the middle, his back to the camera, symmetrical, polaroid photography, highly detailed, crisp quality
Tilt-Shift- photo of construction site, workers, tilt shift effect, bokeh, Nikon
Product Shot- Product shot of nike shoes, with soft vibrant colors, 3d blender render, modular constructivism, blue background, physically based rendering, centered
Long Exposure - An aerial view, city at night, long exposure, instagram contest

Photography Styles

Portrait- Portrait, storm trooper with his beautiful wife on his wedding day
Color-Splash- Color splash, wide photo, phone booth in the middle of empty street, detailed, mist, soft vignette
Monochrome- Photo of staircase in abandoned building, symmetrical, monochrome photography, highly detailed, crisp quality and light reflections, 100mm lens



Lenses
Telephoto- Alligator emerging from water, telephoto lens

Fish-eye- Night club, people dancing, Fish-eye lens

800mm- Photo of hummingbird, 800mm lens

Macro- ladybug, macro lens



Lighting

Nostalgic- Fallout concept art, school interior, 3d render, grim, nostalgic lighting, unreal engine 5

Purple Neon- Fallout concept art, school interior, 3d render, grim, realistic, realistic purple neon lighting, unreal engine 5

Sun Rays- Fallout concept art, school interior, 3d render, grim, sun rays, sun rays coming through window, unreal engine 5




Art Mediums

Chalk- walter white, sidewalk painting, chalk

Graffiti- graffiti art, astronaut holding a super soaker

Water Colors- sunset behind mountains, painting, water colors, detailed, vaporwave aesthetic

Oil Painting- Oil painting, Rick Sanchez, contest winner

Fabric- Crochet doll of Spiderman, studio lighting

Pencil Drawing- Emma Watson, pencil painting

Wood- Modern table design,  made of wood, studio lighting 

Clay- Clay model, throne from Game of Thrones

Amigurumi - amigurumi, European woman, casual dressed
when using amigurumi, ANY thing will become knitted/woven. Even an apple (or a tree or a girl or something else) will be knitted




List of artists by style

Portrait- Derek Gores, Miles Aldridge, Jean Baptiste-Carpeaux, Anne-Louis Girodet

Landscape- Alejandro Bursido, Jacques-Laurent Agasse, Andreas Achenbach, Cuno Amiet

Horror- H.R.Giger, Tim Burton, Andy Fairhurst, Zdzislaw Beksinski

Anime- Makoto Shinkai, Katsuhiro Otomo, Masashi Kishimoto, Kentaro Miura

Sci-fi- Chesley Bonestell, Karel Thole, Jim Burns, Enki Bilal

Photography- Ansel Adams, Ray Earnes, Peter Kemp, Ruth Bernhard

Concept artists (video game)- Emerson Tung, Shaddy Safadi, Kentaro Miura




Portrait Artists
Using an artist that is known for doing portraits can be very helpful in creating a speciﬁc style. In all the
images below everything was kept the same including the seed, All the differences are caused by the artist
chosen. As you can see some artists have a very profound effect and others have just a subtle effect.

Landscape Artists
When making a landscape it's smart to give a set of day like morning, noon or night time and to set the
season. Notice that some artists only inﬂuence the output subtly while others change it drastically

Horror Artists
Horror artists are known for having chilling images but they can be used to make pleasing images mixed
with other artists. See the page on mixed artist later in the book.

Anime Artists
It’s important when using anime artists to keep in mind the style they focus on and what time period they are
from

Sci-ﬁ Artists
Choosing the right artist can drastically change the output. Science ﬁction artists tend to have very distinctive
styles. Remember that you can not only use traditional art mediums but also artists from ﬁlms.

Photography Artists
Dont forget that you can use noted photographers in your prompts. Try to use landscape or portrait
photographers depending on what you are focusing on.

Concept Artists (Video Games)
When it comes to concept artists some of them will make scenes better while others will make better
character designs

3D illustrations
Stable diffusion can be used to create any 3D scene or object you can imagine!

Isometric assets- isometric kitchen in a cutaway box, isometric,  tiny, cute, soft smooth lighting, soft colors, 100mm lens, 3d blender render
Low Poly- kawaii, low poly, squirrel character, 3d isometric render, white background, ambient occlusion, unity engine
Pixar Renders- 3d fluffy Lion, close-up, cute, adorable, cute big circular reflective eyes, long fuzzy fur, Pixar render, unreal engine, cinematic, intricate detail, cinematic
3D Item Render- isometric Alarm Clock, isometric, tiny, soft smooth lighting, soft colors, 3d blender render, trending on polycount, modular constructivism, physically based rendering

More illustrations

Vector- living room, vector illustration, Flat Style, pastel color palette
Comic- Retro comic style artwork, benedict cumberbatch, highly detailed, comic book cover, symmetrical, vibrant
Caricature- Caricature art, spiderman, sitting , chair, drinking beer, on Charlie Hebdo
Propaganda- Poster, USSR propaganda poster, Eat Oreo!
Psychedelic Art- dear face, Hypnotic illustration, hypnotic psychedelic art, by Dan Mumford, pop surrealism, dark glow neon mystical, Behance
Splash Art- mage, channeling arcane magicks, armored, Splash art, mana shooting from his hands, mystical energy in the air, action shot, heroic fantasy art, special effects, hd octane render
Stickers- Die-cut sticker, Cute, kawaii, Goldendoodle character, sticker, white background, illustration minimalism, vector, pastel colors
Simple feelings modifiers can set the atmosphere of the scene!
Positive emotions
Cosy- Cosy vintage bedroom, octane render, by weta digital, exotic colorful pastel, ray traced lighting, reflections
Romantic- couple shopping, romantic lighting
Joyful- Joyful, husky puppy, splashing water, canon eos r3
Energetic- Energetic painting, pool with flamingos
Hope- Woman, filled with hope, beautiful dress, running, beach
Lust- couple, Painting, filled with lust, by mike mignola
Peaceful- Japanese city street, peaceful, dreamy, soft colors, studio ghibli style
Satisfaction- Old man, looking at viewer, filled with satisfaction, Canon EOS 5D Mark IV

Negative emotions

Depressing- Depressing photo, futuristic park
Loneliness- Girl, sitting in window, reading a book, loneliness
Grim- lake with ducks, grim painting
Regret- man, looking at viewer, painting, filled with regret
Suffering- woman, suffering, sitting on a bench, forest, Digital painting, by goro fujita
Hopelessness- Man, hopelessness, black and white, looking at viewer, sketch, intricate details
Fear- Child running towards the camera, in fear, by atey ghailan, by mike mignola
Vibrant keywords: Weirdcore, Acidwave, Dreamcore, Vaporwave

Gloomy: 
Liminal Space- Flooded, liminal space,underground city carpark, lighting with lensflares, photorealistic 8k, eerie
After Hours- After hours, stairs to the park, complex background, stuff in the background, highly detailed, (gloomy:1.3), dark, dimmed, hdr, vignette, grimy, (slate atmosphere:0.8)
Brutalism- Building, architecture, brutalism 
Post-Apocalyptic- Post-Apocalyptic town, houses, cars

Magic words:

HDR, UHD, 64K- Quality words like HDR, UHD, 4K, 8k, and 64K can make a dramatic difference.

Greg rutkowski- Adds epicness to the photo, often suitable for fantasy art

Highly detailed- Quality words like highly detailed can make a dramatic difference.

Studio lighting- Studio lighting could really add some nice texture to the image

Professional- Adding professional, can greatly improve the color contrast and details in the image

Trending on artstation- without description

Unreal engine- a magic word that adds very realistic 3D renderings

Vivid Colors- Adding Vivid Colors, adds life to your images

Bokeh- Bokeh blurs the background and highlights the subject. It’s like iPhone portrait mode.

High resolution scan- Want a historic looking photo? Add "High resolution scan"
