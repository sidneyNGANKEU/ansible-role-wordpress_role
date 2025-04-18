# Rôle Ansible pour WordPress

Installe WordPress avec MariaDB sur Ubuntu/Debian ou Rocky/RHEL.

## Variables à modifier
Éditez `defaults/main.yml` pour :
- Changer les mots de passe
- Modifier le répertoire d'installation

## Après installation
1. Modifiez manuellement les clés de sécurité dans :
   `{{ wordpress_install_dir }}/wp-config.php`
2. Accédez à http://votre-serveur pour terminer l'installation