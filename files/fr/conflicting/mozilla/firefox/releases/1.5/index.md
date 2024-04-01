---
title: Adaptation des applications XUL pour Firefox 1.5
slug: conflicting/Mozilla/Firefox/Releases/1.5
original_slug: Mozilla/Firefox/Releases/1.5/Adapting_XUL_Applications_for_Firefox_1.5
---

{{FirefoxSidebar}}

Cette page contient une liste des modifications de [Firefox 1.5](/fr/Firefox_1.5) qui concernent les développeurs XUL.

### Modifications spécifiques

- [Modifications de l'API Tree](/fr/Modifications_de_l'API_Tree)
- [Caractères internationaux dans du JavaScript XUL](/fr/Caractères_internationaux_dans_du_JavaScript_XUL) (seules les extensions contenant des caractères non-ASCII sont affectées)
- [Modifications avec XMLHttpRequest](/fr/Changements_dans_XMLHttpRequest_pour_Gecko_1.8)
- [Modifications XUL pour Firefox 1.5](/fr/Modifications_XUL_pour_Firefox_1.5)
- [XPCNativeWrapper](/fr/XPCNativeWrapper) sont activés par défaut et leurs comportements diffèrent légèrement par rapport à 1.0.x
- Une méthode plus simple [d'enregistrement chrome](/fr/Enregistrement_chrome) rend obsolète contents.rdf
- Pour les menus contextuels avec overlay&nbsp;: la fonction `gContextMenu.linkURL()` a été renommée en `gContextMenu.getLinkURL()` et `linkURL` est maintenant une propriété. Pour l'utiliser de manière rétrocompatible&nbsp;:
  url = 'getLinkURL' in gContextMenu&nbsp;? gContextMenu.getLinkURL()&nbsp;: gContextMenu.linkURL();

### Autres informations

- [Comment tester la version d'une application en utilisant nsIXULAppInfo](/fr/Utilisation_de_nsIXULAppInfo)
- [MozillaZine](http://kb.mozillazine.org/Dev_:_Extensions_:_Cross-Version_Compatibility_Techniques)
