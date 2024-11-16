<div align="center">

# SEAL <br/> The Search Engine Abstraction Layer <br/> was moved

</div>

<div align="center">
    <img alt="SEAL Logo with an abstract seal sitting on a telescope." src="https://avatars.githubusercontent.com/u/120221538?s=400&v=6" width="200" height="200">
</div>

<div align="center">Logo created by <a href="https://cargocollective.com/meinewilma">Meine Wilma</a></div>

## New Home

The Schranz Search Project better known as **SEAL (Search Engine Abstraction Layer)** was moved to the new [PHP CMS-IG Organisation](https://github.com/PHP-CMSIG/) as a cooperation between different Content Management Systems.

## Migration

To upgrade use search and replace also have a look at the .examples changes to better understand the upgrade.

 - Package names:
    - `schranz-search/seal` -> `cmsig/seal`
    - `schranz-search/seal-...-adapter` -> `cmsig/seal-...-adapter`
    - `schranz-search/laravel-package` -> `cmsig/seal-laravel-package`
    - `schranz-search/mezzio-module` -> `cmsig/seal-mezzio-module`
    - `schranz-search/spiral-bridge` -> `cmsig/seal-spiral-bridge`
    - `schranz-search/yii-module` -> `cmsig/seal-yii-module`
    - `schranz-search/symfony-bundle` -> `cmsig/seal-symfony-bundle`

 - Namespaces:
    - `Schranz\Search\SEAL` -> `CmsIg\Seal\`
    - `Schranz\Search\Integration` -> `CmsIg\Seal\Integration`

 - Config Files:
    - `schranz_search.*` -> `cmsig_seal.*`

 - Config, Service names, Tagged Services:
    - `schranz_search.*` -> `cmsig_seal.*`

 - Commands:
    - `schranz:search:*` -> `cmsig:seal:*`

 - Spiral Integration Changes:
   - `SearchBootloader` -> `SealBootloader`
   - `SearchConfig` -> `SealConfig`
   - `seal.php` -> `cmsig_seal.php`

 - Symfony Integration Changes:
   - `SearchBundle` -> `SealBundle`
   - `seal.yaml` -> `cmsig_seal.yaml`

 - Laravel Integration Changes:
   - `SearchProvider` -> `SealProvider`
   - `seal.php` -> `cmsig_seal.php`
