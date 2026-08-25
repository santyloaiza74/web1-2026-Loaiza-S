# Declaración de uso de IA

> Obligatoria en todas las prácticas. Si usaste un asistente, descríbelo aquí con
> precisión. Si NO usaste ninguno, escribe eso y explica cómo resolviste la parte
> más difícil por tu cuenta — también cuenta como declaración válida.
>
> Recuerda: código de IA sin declarar se califica en CERO y no admite reintento.
> Declararlo honestamente NO baja tu nota. Lo que se evalúa es tu capacidad de auditar.

## Herramientas que usé
<!-- Ej.: GitHub Copilot en VS Code, ChatGPT, Claude, Cursor. Indica también si no usaste ninguna. -->
Gemini Google
## Qué le pedí
<!-- Escribe el prompt real, no un resumen idealizado -->

```
necesito devolverme porque no complete el perfil antes de hacer el merge, dame los comandos paso a paso para hacerlo y que el trabajo me quede bien
```

## Qué me devolvió
<!-- Pega el fragmento relevante -->

```javascript
# Eliminar el tag en local y en el remoto
git tag -d practica-00-v1
git push origin --delete practica-00-v1

# Deshacer el merge en tu rama local manteniendo tus archivos intactos
git reset --soft HEAD~1
```

## Qué estaba mal
<!-- La parte más importante del documento. Sé específico: qué falla, en qué caso,
     por qué el código parecía correcto pero no lo era. Si de verdad no encontraste
     ningún error, explica cómo lo verificaste (qué casos probaste). -->

     Tengo el perfil en la carpeta de practica, por eso al hacer el merge no se veia reflejado en el README.md del la rama main

## Qué corregí y por qué
<!-- Tu código final y el razonamiento del cambio -->

```javascript
simplemente copiar y pegar lo que ya habia hecho en la carpeta al archivo de la rama para que quedara la informacion donde debe ir
```

## Qué escribí yo desde cero
<!-- Qué partes no delegaste, y por qué decidiste no delegarlas -->
completar el perfil

## Reflexión
<!-- ¿Te ahorró tiempo de verdad, o lo perdiste depurando? ¿Volverías a usarlo para esto? -->
poner mas atencion donde se tienen los archivos para evitar ese tipo de confuciones