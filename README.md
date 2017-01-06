## Epicodus Work

### Ruby

#### Week 1

* Ping Pong
* Title Case
* Leetspeak
* Queen Attack
* Clock Angle
* Scrabble
* Number to word converter(numberword)
* Title Case
* Scrabble Score (scrabble)
* Rock Paper Scissors
* Find and Replace
* Coin Combinations (make-change)
* Anagrams
* Allergens
* Word Count (Independent Project)

#### Week 2

* Triangles         https://github.com/lukeephilips/triangle_counter
* Parcels           https://github.com/lukeephilips/parcel_calc
* Hashy             https://github.com/lukeephilips/Hashy
* Task List         https://github.com/margie-ynm/task-list
* Passport          https://github.com/margie-ynm/passport
* Tamagotchi        https://github.com/margie-ynm/tamagotchi
* Dealership        https://github.com/caitlinashtari/dealership
* Contacts  (Solo)
* Dictionary (Independent Project)  https://github.com/LawlietBlack/dictionary

#### Week 3

* To Do List                        https://github.com/accua/to_do_list_psql
* Animal Shelter                    https://github.com/kftwotwo/animal_shelter
* Express                           https://github.com/margie-ynm/express
* Hair Salon (Independent Project)  https://github.com/lawlietblack/salon

#### Week 4

* Surveys                     https://github.com/jrinard/survey_ruby
* Recipes                     https://github.com/tyedye105/rrecipes
* Shoes (Independent Project) https://github.com/LawlietBlack/shoes

#### Week 5 (Team Week)

* Learning Playlist https://github.com/LawlietBlack/learning-playlist (External Repo)

### JavaScript

#### Week 1

* calculator		https://github.com/kftwotwo/calculator_js
* journal 		https://github.com/kftwotwo/journal_js
* memory game		https://github.com/kftwotwo/memory_js
* alarm clock 		https://github.com/haleyswain/weather
* weather		https://github.com/haleyswain/alarm-clock
* doctors		https://github.com/LawlietBlack/doctors

### Drupal (Self-Study)

#### Week 1

* Cameron's Coffee(hipster-haus)
* Fan Site(universe)
* Portfolio(lawlietblack)

#### Week 2

* Module Playground
  * Sum



### Drupal Setup Instructions:

1. Download Drupal version 7.51

2. Replace the sites folder with the enclosed sites folder

3. Import the Database Dump

  a. Open phpMyAdmin and click on the "Import" tab.

  b. Leave all the default settings and make sure the character set is "utf-8"

  c. Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file we included in our sites/db-backup folder. It's okay to leave it zipped.

  d. Then click the "Go" button on the bottom left.

4. Create the Database User (not needed if using Acquia Dev Desktop)

  a. Lastly, we must recreate the database username/password that Drupal uses to store things in the database. We do this the same way we did when we created the database.

  b. After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

  c. Use the same username and password from before. (If we have forgotten what that was, we can always find that information in settings.php, or in the PDO Exception error message we saw displayed in the browser.)

  d. After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.
