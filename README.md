Class Thaumatized : Human  
{  
  ShortAlias = "Thauma";  
  Websites = new string[]  
  {  
    "https://thaumatek.fi",  
    "https://pussyhub.fi",  
    "https://ankkapeli.fi",  
  };  
  Occupation = Conscript;  
  
  //Values may not be accurate
  ProgrammingSkills = new ProgrammingSkill[]  
  {  
    new ProgrammingSkill("C#", 0.8f),  
    new ProgrammingSkill("Python", 0.5f),  
    new ProgrammingSkill("Javascript", 0.4f),   
    new ProgrammingSkill("PHP", 0.7f),  
    new ProgrammingSkill("C++", 0.1f),  
    new ProgrammingSkill("C", 0.05f),  
  };  
  
  //No way these are accurate!  
  IntrestWeights = new NamedWeight[]  
  {  
    new NamedWeight("Software developement", 0.9f),  
    new NamedWeight("3D printing", 0.8f),  
    new NamedWeight("3D modeling", 0.75f),  
    new NamedWeight("Computer hardware", 0.7f),  
    new NamedWeight("Hosting", 0.6f),  
    new NamedWeight("Social life", 0.2f),  
    new NamedWeight("Music", float.MinValue),  
  };  
}  
