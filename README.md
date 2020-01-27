# generator-jhipster-entity-audit [![NPM version][npm-image]][npm-url] [![Build Status][github-actions-image]][github-actions-url] [![Dependency Status][daviddm-image]][daviddm-url]
> JHipster module to enable entity auditing and to add audit log page

## Usage

This is a [JHipster](http://jhipster.github.io/) module, that is meant to be used in a JHipster application.

The module will extend the selected entities and its DTOs with `AbstractAuditingEntity` and `AbstractAuditingDTO` class respectively to enable audits, hence make sure that your entities/DTOs doesn't have any super class.

The Audit log page is optional and can be added by choosing the option while running the generator

jhipster-entity module will register itself as a hook for Jhipster and the question to enable audit will available during future entity generation as well

### Installation

As this is a [JHipster](http://jhipster.github.io/) module, we expect you have [JHipster and its related tools already installed](http://jhipster.github.io/installation.html).

This module requires Jhipster version greater than 3.0 in order to work

```bash
npm install -g generator-jhipster-entity
```

Then run the module on a JHipster generated application:

```bash
yo jhipster-entity
```

If you want don't want to answer each question you can use

```bash
yo jhipster-entity default
```
This will enable auditing for all available entities (only ones created by the jhipster:entity generator) and add the audit log page under admin

## License

Apache-2.0
