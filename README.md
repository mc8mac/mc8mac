cad = ['Hello World, I’m Marcos Machado, an 18yo ETI Minor Student at Instituto Superior Técnico.',\
       'I'm a young programmer from Madeira, Portugal.',\
       'Basketall and chess enthusiast.']\

def readme_txt(cad):
  if len(cad) == 1:
    return cad
  return cad[0] + '\n' + readme_txt(cad[:1])
  
  print(readme_txt(cad))
