ISSUES

#Yes = [1]  No = [0]  In progress = [2]     check what is a glider!!!

1. Init Matrix    [1]
2. Print Matrix   [1]
3. do_game()    [2]
  - iterate [1]
  - count neighbours
  - check rules
    {
      1) manje od 2. komsije = mrtav
      2) vece ili jednako od 2. komsije = next generation, repopulation
      3) vece od 3. komsije = over population, mrtav
      4) jednako 3. komsije = reprodukcija
    }
  - write
4. Swap
