<div align="center">
  <img src="https://github.com/MaCo-CC238-SW63/Report/blob/main/Resources/UPC_logo.png?raw=true" alt="Logo-UPC" width="150">

## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2024-2

**Curso:** Aplicaciones para Dispositivos Móviles

**Sección:** SW63

**Profesor:** Jorge Luis Mayta Guillermo

----
## Informe de Trabajo Final
### MaCo

### CambiaZo
#### Relación de integrantes 
| Integrante                  | Código         |
|---------------------------------|----------------|
| Huamani Mandujano, Joseph Alexis         | U20221A133     |
| Mendoza Carrion, Mathias Andre          | U202216282     |
| Quispe Andia, Jeremy Joel      | U202216279     |
| Santisteban Palomino, Ian Haziel Donato | U202214059     |

</div>


<br><div align="center"><h3>Agosto 2024</h3></div><br>
---
<div style="text-align: justify;">
  
# Capítulo I: Introducción
## 1.1 Startup Profile
### 1.1.1 Descripción de la Startup

**Nombre:**  TechZo

**Área:**  Innovación tecnológica y Reutilización

TechZo es una startup que está conformada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC) de la facultad de ingeniería. La compañía pretende abordar y contribuir con el crecimiento del desarrollo sostenible del país, alentando a la cultura de consumo responsable y una economía circular. Es por ello que se ha propuesto como medida de solución la creación de la aplicación web CambiaZo.

* **Misión:**  La misión de TechZo como empresa es promover un estilo de vida sostenible y consciente, facilitando el intercambio de bienes y artículos entre usuarios de manera segura y justa sin necesidad de realizar transacciones monetarias. Buscamos presentar un concepto sólido y alineado con las tendencias de consumo responsable y economía circular, permitiendo a los usuarios intercambiar objetos que ya no desean por otros que necesitan o les interesan actualmente.<br><br>Entendemos la importancia de la seguridad y veracidad en el proceso del intercambio de artículos, de modo que sea justo y beneficioso para ambas partes. Por lo tanto, nos esforzamos para asegurar que los usuarios puedan visualizar todos los detalles de los productos ofrecidos para intercambiar, y que puedan despejar todas sus dudas antes de realizar el intercambio, para que de este modo no haya ninguna insatisfacción por parte de los usuarios. Además, con la aplicación web CambiaZo, queremos apoyar a la comunidad agregando una opción para que los usuarios puedan realizar donaciones de artículos a personas de escasos recursos económicos.


* **Visión:**  La visión de Techzo es convertirse en la principal plataforma digital de intercambio de productos básicos que promueva una vida sostenible y consciente a nivel mundial. Nos esforzamos por ser líderes en el cambio hacia una economía circular, donde cada acto de comunicación coopere a reducir nuestro impacto en el medio ambiente y a construir una comunidad más solidaria y conectada.

* **Valores:**  

  *  **Seguridad y privacidad:** La privacidad es prioritaria, nos preocupamos para que nuestros usuarios sientan que los datos que nos otorgan están seguros y mantenidos en privacidad. Por ello, les otorgamos a nuestros usuarios control sobre ello. Además, sabemos que las medidas sólidas de seguridad, incluido el cifrado de datos en tránsito y reposo, junto con prácticas sólidas en el diseño de la base de datos, resguardan la información sobre nuestros usuarios.

  * **Innovación:** Estar en constante búsqueda de nuevas formas de mejorar la experiencia de los usuarios a través de la tecnología y la creatividad, manteniendo la aplicación a la vanguardia.

  * **Aprendizaje Continuo:** Fomentar un ambiente en el que los miembros del equipo estén dispuestos a aprender y mejorar constantemente, tanto en términos de sostenibilidad como de consumo responsable.

  * **Calidad:** Compromiso con la excelencia en el diseño de la aplicación web y la funcionalidad de esta misma, asegurándonos de que cumpla con las expectativas más altas de nuestros usuarios.

  * **Compromiso con el usuario:** Poner las necesidades y deseos de los usuarios en el centro de todas las decisiones, asegurando que la aplicación satisfaga sus expectativas y mejore su experiencia realizando intercambios.

  * **Respeto a la diversidad:**  Valorar y respetar las diferencias culturales, étnicas, de género y de opinión, tanto en el equipo interno como en la comunidad de usuarios.

 ### 1.1.2 Perfiles de integrantes del equipo

A continuación, presentaremos los perfiles de los integrantes del equipo encargado de desarrollar el proyecto. Cada uno de nuestros miembros aporta una combinación única de habilidades y perspectivas que son fundamentales para el éxito del proyecto.

| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Huamani Mandujano, Joseph Alexis - u20221a133**             |Mi nombre es Joseph Huamani, soy estudiante de 5to ciclo en la carrera de Ingeniería de Software en la UPC. La razón por la cual elegí esta carrera es porque desde pequeño siempre me ha gustado la tecnología, el cómo es el funcionamiento y la creación de los programas que uso en mí día a día.  Por ello, en este curso me  comprometo a ser un buen integrante para mi grupo y dar lo  mejor de mí en los trabajos con las habilidades técnicas como dominio en los lenguajes C++, Python y Javascript y habillidades blandas como trabajo en equipo, responsabillidad y resolución de problemas. | <img src="https://github.com/MaCo-CC238-SW63/Report/blob/main/Resources/Profiles/josephhuamani.png?raw=true" alt="Imagen de Joseph Huamani" />                |
| **Mendoza Carrión, Mathias André - u202216282** |Soy Mathias Andre Mendoza Carrión, un estudiante de 19 años de Ingeniería de Software en el quinto ciclo. Me caracterizo por ser organizado, trabajar bien en equipo y ser responsable. En este momento, mi enfoque principal es el aprendizaje profundo y práctico en el desarrollo de software. Aspiro a dominar nuevas tecnologías y habilidades, así como a comprender en detalle los principios fundamentales detrás del desarrollo de aplicaciones.| <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Profiles/mathias.jpg?raw=true" alt="Imagen de Mathias Mendoza"/> |
| **Quispe Andia, Jeremy Joel - u202216279** |Mi nombre es Diego Anderson Criollo de La Cruz, soy estudiante de 5to ciclo de la carrera de Ingeniería de Software. Me gusta mucho emplear soluciones creativas y que busquen eficiencia para poder aborder de esta forma cualquier desafío de la mejor manera. Como miembro del grupo, pretendo aportar con todos mis conocimientos en el desarrollo web tanto como en el front-end y back-end,  además de siempre colaborar con mis ideas y soluciones ante cualquier dificultad que se presente en el desarrollo. Espero poder aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del desarrollo del proyecto.| <img src="https://github.com/MaCo-CC238-SW63/Report/blob/main/Resources/Profiles/jeremyquispe.jpeg?raw=true" alt="Imagen de Jeremy Quispe"/>                 |
| **Santisteban Palomino, Ian Haziel Donato - u202214059**     |Mi nombre es Ian Haziel Donato Santisteban Palomino y estoy cursando el quinto ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/MaCo-CC238-SW63/Report/blob/main/Resources/Profiles/iansantisteban.png?raw=true" alt="Imagen de Ian Santisteban"/> |


## 1.2 Solution Profile
La propuesta se basa en una aplicación móvil llamada CambiaZo, diseñada para asistir en el intercambio y donación de productos que los usuarios ya no utilizan. Esta aplicación móvil conectará a usuarios de distintas partes a través de sus dispositivos y ayudará a que puedan obtener los objetos que desean a través del trueque con otros usuarios, además ayudará a facilitar las formas de donar a personas de escasos recursos económicos.


### 1.2.1 Antecedentes y problemática
Se sabe que la cultura de desarrollo sostenible está tomando impulso en los últimos años. Es por ello que diversas empresas del mundo están empezando a implementar este pensamiento en sus trabajadores y políticas. A continuación, se explicará con más detalle el desafío al cual se enfrenta este nuevo estilo de vida.

Según un reporte del portal INFOBAE del presente año 2024, se menciona sobre las estimaciones realizadas de la ONU sobre el crecimiento de la población mundial. De acuerdo a ello, se espera que la población mundial aumente en 2000 millones de personas en los próximos 30 años, llegando a una cifra total de 9700 millones de personas para el año 2050. Cada una de estas personas generará sus propios residuos, que multiplicados por toda la población mundial se convierten en una cifra gigantesca. Es frente a este futuro escenario en donde entra nuestra propuesta de solución, CambiaZo.

Para explicar con más detalle esta situación, como grupo, usaremos la metodología de las 5W y 2H para darle más énfasis a los antecedentes y problemáticas a las que se enfrenta nuestra iniciativa de cambio:

**5W's y 2H's**

* **What?**
La cantidad de residuos que se generan a diario por cada persona del mundo generan un impacto negativo en el medio ambiente y en la conservación de los recursos básicos del planeta.<br><br>


* **Why?**
Debido a que muchas personas no toman la iniciativa de darle un nuevo uso a aquellas pertenencias que ya no necesitan más y simplemente deciden desecharlas, sin conocer las consecuencias que esto podría ocasionar a largo plazo.<br><br>

* **Who?**
Público en general y personas que más necesitan de apoyo de recursos.<br><br>

* **When?**
Esta problemática es una constante con el pasar de los años ya que recién es que se está popularizando la cultura de reutilización y desarrollo sostenible, debido a que desde siempre se ha optado en primera instancia por solo desechar y no reutilizar.<br><br>

* **Where?**
Si bien es una problemática que persiste en todo el mundo, nos centraremos en un inicio en la población peruana.<br><br>

* **How?**
Se implementará una propuesta de solución mediante el desarrollo de una aplicación móvil que permita a los usuarios publicar posts de objetos que deseen intercambiar por otras pertenencias, además de permitir realizar donaciones a organizaciones benéficas. Todo ello en una plataforma intuitiva, fácil de manejar y con opciones de personalización.<br><br>

* **How much?**
El presupuesto varía dependiendo de cuanta información se
requiera para el desarrollo del aplicativo web. Sin embargo se considera un aproximado de s/. 7 000.

</div>

