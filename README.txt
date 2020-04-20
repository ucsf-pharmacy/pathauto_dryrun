Provides method to return patterned alias string and do nothing else.

With dependency injection:
$alias = $this->pathautoDryrun->getAlias($entity);

With global function:
$alias = \Drupal::service('pathauto_dryrun.generator')->getAlias($entity);

Installation:
Enable module as usual.