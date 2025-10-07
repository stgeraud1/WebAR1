Compile les images à détecter : https://hiukim.github.io/mind-ar-js-doc/tools/compile/

Le dossier "Images" sert uniquement à mettre les images à détecter (pour rappel mais ne sert pas pour le code).

Le dossier "animations" puis les dossiers suivant (targetO et target1) servent à mettre les sequences PNG. Les sequences PNG doivent être nommé : frame_000.png

Le dossier "audio" puis les dossiers suivant (targetO et target1) servent à mettre les sons. Les sons doivent être nommé : audio_000.mp3

Le dossier "models" puis les dossiers suivant (targetO et target1) servent à mettre les modèles 3D. Les modèles 3D doivent être nommé : model.glb

Le dossier "targets" contient le fichier qui compile les images à détecter. Le fichier doit être nommé : targets.mind

Les sous-dossier target0 et target1 définissent l'image à détecter (la première ou la deuxième), car on peut détecté plusieurs images sur la même pages. Ici j'en ai mis 2 mais on peut en mettre plus (il faut modifier le code html en conséquence).
