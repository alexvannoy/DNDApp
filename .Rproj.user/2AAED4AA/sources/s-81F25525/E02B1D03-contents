Character <- R6::R6Class(
  classname = "DNDCharacter",
  public = list(
    race = NULL,
    speed = NA,
    background = NULL,
    alignment = NULL,

    totalLevel = NA,
    barbarianLevel = NA,
    bardLevel = NA,
    clericLevel = NA,
    druidLevel = NA,
    fighterLevel = NA,
    monkLevel = NA,
    paladinLevel = NA,
    rangerLevel = NA,
    rogueLevel = NA,
    sorcererLevel = NA,
    warlockLevel = NA,
    wizardLevel = NA,
    #TODO: Add artificer

    healthPoints = NA,
    armorClass = NA,
    proficiencyBonus = NA,

    # TODO: Figure out this schema
    # level, name, description, damage dice?
    spellList = data.frame(),
    # TODO: Add spell modifier
    # TODO: Add attack modifier

    toolProficiencies = c(),
    weaponProficiencies = c(),
    languageProficiencies = c(),
    savingThrowProficiencies = c(),
    skillProficiencies = c(),

    strength = NA,
    dexterity = NA,
    constitution = NA,
    intelligence = NA,
    wisdom = NA,
    charisma = NA,

    # TODO: Add inventory?
    # TODO: Add attacks?
    # TODO: Add personality traits?
    # TODO: Add ideals?
    # TODO: Add Bonds?
    # TODO: Add flaws?
    # TODO: Add features and traits

    initialize = function(race, background, alignment) {
      self$race <- race
      # TODO: Add additional init steps for speed?
      self$background <- background
      self$alignment <- alignment
      invisible(self)
    }
  )
  # Do you even need private methods?
  # Maybe the level up functions???
)
