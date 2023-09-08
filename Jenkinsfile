pipeline {
  agent any

  tools{
    nosejs "node"
  }

  parameters{
    string(name: 'container_name', defaultValue: 'pagina_web', description: 'Nombre del contenedor del docker')
    string(name: 'image_name', defaultValue: 'pagina_img', description: 'Nombre de la imagen docker.')
    string(name: 'tag_image', defaultValue: 'lts', description: 'Tag de la imagen de la pagina.')
    string(name: 'container_port', defaultValue: 80, description: 'Puerto que usa el contenedor')
  }

  stages{
    stage('install'){
      git branch
  }
}
