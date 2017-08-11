## Module Report
### Unknown Global

**Global**: `Ember.VERSION`

**Location**: `addon/index.js` at line 11

```js
*/

if (Ember.VERSION.match(/^1\.([0-9]|1[0-2])\./)) {
  throw new EmberError("Ember Data requires at least Ember 1.13.0, but you have " +
                        Ember.VERSION +
```

### Unknown Global

**Global**: `Ember.VERSION`

**Location**: `addon/index.js` at line 13

```js
if (Ember.VERSION.match(/^1\.([0-9]|1[0-2])\./)) {
  throw new EmberError("Ember Data requires at least Ember 1.13.0, but you have " +
                        Ember.VERSION +
                        ". Please upgrade your version of Ember, then upgrade Ember Data.");
}
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `addon/-debug/index.js` at line 37

```js
      return modelClass.__mixin.detect(addedModelClass.PrototypeMixin);
    }
    if (Ember.MODEL_FACTORY_INJECTIONS) {
      modelClass = modelClass.superclass;
    }
```

### Unknown Global

**Global**: `Ember.FEATURES`

**Location**: `addon/-private/features.js` at line 4

```js

export default function isEnabled() {
  return Ember.FEATURES.isEnabled(...arguments);
}

```

### Unknown Global

**Global**: `Ember.Namespace`

**Location**: `addon/-private/core.js` at line 20

```js
  @static
*/
const DS = Ember.Namespace.create({
  VERSION: VERSION,
  name: "DS"
```

### Unknown Global

**Global**: `Ember.libraries`

**Location**: `addon/-private/core.js` at line 25

```js
});

if (Ember.libraries) {
  Ember.libraries.registerCoreLibrary('Ember Data', DS.VERSION);
}
```

### Unknown Global

**Global**: `Ember.libraries`

**Location**: `addon/-private/core.js` at line 26

```js

if (Ember.libraries) {
  Ember.libraries.registerCoreLibrary('Ember Data', DS.VERSION);
}

```

### Unknown Global

**Global**: `Ember.Date`

**Location**: `addon/transforms/date.js` at line 5

```js
import { deprecate } from '@ember/debug';

Ember.Date = Ember.Date || {};

/**
```

### Unknown Global

**Global**: `Ember.Date`

**Location**: `addon/transforms/date.js` at line 5

```js
import { deprecate } from '@ember/debug';

Ember.Date = Ember.Date || {};

/**
```

### Unknown Global

**Global**: `Ember.Date`

**Location**: `addon/transforms/date.js` at line 19

```js
 @deprecated
 */
Ember.Date.parse = function(date) {
  // throw deprecation
  deprecate(`Ember.Date.parse is deprecated because Safari 5-, IE8-, and
```

### Unknown Global

**Global**: `Ember.OrderedSet`

**Location**: `addon/-private/system/ordered-set.js` at line 4

```js
import Ember from 'ember';

const EmberOrderedSet = Ember.OrderedSet;

export default function OrderedSet() {
```

### Unknown Global

**Global**: `Ember.OrderedSet`

**Location**: `addon/-private/system/ordered-set.js` at line 4

```js
import Ember from 'ember';

const EmberOrderedSet = Ember.OrderedSet;

export default function OrderedSet() {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 174

```js

test("Pushing to the hasMany reflects the change on the belongsTo side - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 221

```js
*/
testInDebug("Pushing a an object that does not implement the mixin to the mixin accepting array errors out - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 174

```js

test("Pushing to the hasMany reflects the change on the belongsTo side - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 175

```js
test("Pushing to the hasMany reflects the change on the belongsTo side - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

  try {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 213

```js
    });
  } finally {
    Ember.MODEL_FACTORY_INJECTIONS = injectionValue;
  }
});
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 221

```js
*/
testInDebug("Pushing a an object that does not implement the mixin to the mixin accepting array errors out - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 222

```js
testInDebug("Pushing a an object that does not implement the mixin to the mixin accepting array errors out - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

  try {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-has-many-test.js` at line 259

```js
    });
  } finally {
    Ember.MODEL_FACTORY_INJECTIONS = injectionValue;
  }
});
```

### Unknown Global

**Global**: `Ember.Inflector`

**Location**: `tests/integration/serializers/rest-serializer-test.js` at line 79

```js
test("modelNameFromPayloadKey returns always same modelName even for uncountable multi words keys", function(assert) {
  assert.expect(2);
  Ember.Inflector.inflector.uncountable('words');
  var expectedModelName = 'multi-words';
  assert.equal(env.restSerializer.modelNameFromPayloadKey('multi_words'), expectedModelName);
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/adapter-interop-test.js` at line 23

```js
  beforeEach() {
    TestAdapter = DS.Adapter.extend();
    oldFilterEnabled = Ember.ENV.ENABLE_DS_FILTER;
    Ember.ENV.ENABLE_DS_FILTER = false;
  },
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/adapter-interop-test.js` at line 24

```js
    TestAdapter = DS.Adapter.extend();
    oldFilterEnabled = Ember.ENV.ENABLE_DS_FILTER;
    Ember.ENV.ENABLE_DS_FILTER = false;
  },

```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/adapter-interop-test.js` at line 30

```js
    run(() => {
      if (store) { store.destroy(); }
      Ember.ENV.ENABLE_DS_FILTER = oldFilterEnabled;
    });
  }
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/push-test.js` at line 715

```js
testInDebug('Enabling Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS should warn on unknown attributes', function(assert) {
  run(() => {
    let originalFlagValue = Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS;
    try {
      Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS = true;
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/push-test.js` at line 717

```js
    let originalFlagValue = Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS;
    try {
      Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS = true;
      assert.expectWarning(() => {
        store.push({
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/push-test.js` at line 732

```js
      }, `The payload for 'person' contains these unknown attributes: emailAddress,isMascot. Make sure they've been defined in your model.`);
    } finally {
      Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS = originalFlagValue;
    }
  });
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/push-test.js` at line 739

```js
testInDebug('Enabling Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS should warn on unknown relationships', function(assert) {
  run(() => {
    var originalFlagValue = Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS;
    try {
      Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS = true;
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/push-test.js` at line 741

```js
    var originalFlagValue = Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS;
    try {
      Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS = true;
      assert.expectWarning(() => {
        store.push({
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `tests/unit/store/push-test.js` at line 756

```js
      }, `The payload for 'person' contains these unknown relationships: emailAddresses,mascots. Make sure they've been defined in your model.`);
    } finally {
      Ember.ENV.DS_WARN_ON_UNKNOWN_KEYS = originalFlagValue;
    }
  });
```

### Unknown Global

**Global**: `Ember.Date`

**Location**: `tests/unit/transform/date-test.js` at line 61

```js
testInDebug('Ember.Date.parse has been deprecated', function(assert) {
  assert.expectDeprecation(() => {
    Ember.Date.parse(dateString);
  }, /Ember.Date.parse is deprecated/);
});
```

### Unknown Global

**Global**: `Ember.ENV`

**Location**: `addon/-private/system/store.js` at line 61

```js
const {
  _Backburner: Backburner,
  ENV
} = Ember;

```

### Unknown Global

**Global**: `Ember._Backburner`

**Location**: `addon/-private/system/store.js` at line 60

```js

const {
  _Backburner: Backburner,
  ENV
} = Ember;
```

### Unknown Global

**Global**: `Ember.beginPropertyChanges`

**Location**: `addon/-private/system/model/model.js` at line 640

```js
  */
  _notifyProperties(keys) {
    Ember.beginPropertyChanges();
    let key;
    for (let i = 0, length = keys.length; i < length; i++) {
```

### Unknown Global

**Global**: `Ember.endPropertyChanges`

**Location**: `addon/-private/system/model/model.js` at line 646

```js
      this.notifyPropertyChange(key);
    }
    Ember.endPropertyChanges();
  },

```

### Unknown Global

**Global**: `Ember.GUID_KEY`

**Location**: `addon/-private/system/model/internal-model.js` at line 118

```js

    // this ensure ordered set can quickly identify this as unique
    this[Ember.GUID_KEY] = InternalModelReferenceId++ + 'internal-model';

    this.store = store;
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `addon/-private/system/relationships/ext.js` at line 13

```js

export const relationshipsDescriptor = computed(function() {
  if (Ember.testing === true && relationshipsDescriptor._cacheable === true) {
    relationshipsDescriptor._cacheable = false;
  }
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `addon/-private/system/relationships/ext.js` at line 40

```js

export const relatedTypesDescriptor = computed(function() {
  if (Ember.testing === true && relatedTypesDescriptor._cacheable === true) {
    relatedTypesDescriptor._cacheable = false;
  }
```

### Unknown Global

**Global**: `Ember.Logger`

**Location**: `tests/test-helper.js` at line 42

```js
    // handle the error.
    if (reason && reason instanceof Error) {
      Ember.Logger.log(reason, reason.stack);
      throw reason;
    }
```

### Unknown Global

**Global**: `Ember._RegistryProxyMixin`

**Location**: `tests/helpers/owner.js` at line 6

```js
let Owner;

if (Ember._RegistryProxyMixin && Ember._ContainerProxyMixin) {
  Owner = EmberObject.extend(Ember._RegistryProxyMixin, Ember._ContainerProxyMixin);
} else {
```

### Unknown Global

**Global**: `Ember._ContainerProxyMixin`

**Location**: `tests/helpers/owner.js` at line 6

```js
let Owner;

if (Ember._RegistryProxyMixin && Ember._ContainerProxyMixin) {
  Owner = EmberObject.extend(Ember._RegistryProxyMixin, Ember._ContainerProxyMixin);
} else {
```

### Unknown Global

**Global**: `Ember._RegistryProxyMixin`

**Location**: `tests/helpers/owner.js` at line 7

```js

if (Ember._RegistryProxyMixin && Ember._ContainerProxyMixin) {
  Owner = EmberObject.extend(Ember._RegistryProxyMixin, Ember._ContainerProxyMixin);
} else {
  Owner = EmberObject.extend();
```

### Unknown Global

**Global**: `Ember._ContainerProxyMixin`

**Location**: `tests/helpers/owner.js` at line 7

```js

if (Ember._RegistryProxyMixin && Ember._ContainerProxyMixin) {
  Owner = EmberObject.extend(Ember._RegistryProxyMixin, Ember._ContainerProxyMixin);
} else {
  Owner = EmberObject.extend();
```

### Unknown Global

**Global**: `Ember.__loader`

**Location**: `tests/helpers/setup-ember-dev.js` at line 9

```js
// Maintain backwards compatiblity with older versions of ember.
let emberDebugModule;
if (Ember.__loader && Ember.__loader.registry && Ember.__loader.registry["ember-metal/debug"]) {
  emberDebugModule = Ember.__loader.require('ember-metal/debug');
}
```

### Unknown Global

**Global**: `Ember.__loader`

**Location**: `tests/helpers/setup-ember-dev.js` at line 9

```js
// Maintain backwards compatiblity with older versions of ember.
let emberDebugModule;
if (Ember.__loader && Ember.__loader.registry && Ember.__loader.registry["ember-metal/debug"]) {
  emberDebugModule = Ember.__loader.require('ember-metal/debug');
}
```

### Unknown Global

**Global**: `Ember.__loader`

**Location**: `tests/helpers/setup-ember-dev.js` at line 9

```js
// Maintain backwards compatiblity with older versions of ember.
let emberDebugModule;
if (Ember.__loader && Ember.__loader.registry && Ember.__loader.registry["ember-metal/debug"]) {
  emberDebugModule = Ember.__loader.require('ember-metal/debug');
}
```

### Unknown Global

**Global**: `Ember.__loader`

**Location**: `tests/helpers/setup-ember-dev.js` at line 10

```js
let emberDebugModule;
if (Ember.__loader && Ember.__loader.registry && Ember.__loader.registry["ember-metal/debug"]) {
  emberDebugModule = Ember.__loader.require('ember-metal/debug');
}

```

### Unknown Global

**Global**: `Ember.name`

**Location**: `tests/helpers/setup-ember-dev.js` at line 17

```js
    return emberDebugModule.getDebugFunction(name);
  } else {
    return Ember[name];
  }
}
```

### Unknown Global

**Global**: `Ember.name`

**Location**: `tests/helpers/setup-ember-dev.js` at line 25

```js
    emberDebugModule.setDebugFunction(name, func);
  } else {
    Ember[name] = func;
  }
}
```

### Unknown Global

**Global**: `Ember.Registry`

**Location**: `tests/helpers/store.js` at line 11

```js
  options = options || {};

  if (Ember.Registry) {
    registry = env.registry = new Ember.Registry();
    owner = Owner.create({
```

### Unknown Global

**Global**: `Ember.Registry`

**Location**: `tests/helpers/store.js` at line 12

```js

  if (Ember.Registry) {
    registry = env.registry = new Ember.Registry();
    owner = Owner.create({
      __registry__: registry
```

### Unknown Global

**Global**: `Ember.Container`

**Location**: `tests/helpers/store.js` at line 21

```js
    owner.__container__ = container;
  } else {
    container = env.container = new Ember.Container();
    registry = env.registry = container;
  }
```

### Unknown Global

**Global**: `Ember.Namespace`

**Location**: `tests/integration/application-test.js` at line 13

```js

const Store = DS.Store;
const Namespace = Ember.Namespace;

let app, App, container;
```

### Unknown Global

**Global**: `Ember.Namespace`

**Location**: `tests/integration/application-test.js` at line 13

```js

const Store = DS.Store;
const Namespace = Ember.Namespace;

let app, App, container;
```

### Unknown Global

**Global**: `Ember.BOOTED`

**Location**: `tests/integration/application-test.js` at line 47

```js
  afterEach() {
    run(app, app.destroy);
    Ember.BOOTED = false;
  }
});
```

### Unknown Global

**Global**: `Ember.BOOTED`

**Location**: `tests/integration/application-test.js` at line 87

```js
  afterEach() {
    run(app, 'destroy');
    Ember.BOOTED = false;
  }
});
```

### Unknown Global

**Global**: `Ember.inject`

**Location**: `tests/integration/application-test.js` at line 108

```js
});

if (Ember.inject && service) {
  module("integration/application - Using the store as a service", {
    beforeEach() {
```

### Unknown Global

**Global**: `Ember.BOOTED`

**Location**: `tests/integration/application-test.js` at line 122

```js
    afterEach() {
      run(app, 'destroy');
      Ember.BOOTED = false;
    }
  });
```

### Unknown Global

**Global**: `Ember.BOOTED`

**Location**: `tests/integration/application-test.js` at line 143

```js
      run(app, app.destroy);
    }
    Ember.BOOTED = false;
  }
});
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/injection-test.js` at line 10

```js

let env, hasFactoryFor, originalLookupFactory, originalOwnerLookupFactory, originalFactoryFor;
let originalMODEL_FACTORY_INJECTIONS = Ember.MODEL_FACTORY_INJECTIONS;

const model = {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/injection-test.js` at line 10

```js

let env, hasFactoryFor, originalLookupFactory, originalOwnerLookupFactory, originalFactoryFor;
let originalMODEL_FACTORY_INJECTIONS = Ember.MODEL_FACTORY_INJECTIONS;

const model = {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/injection-test.js` at line 84

```js
module('integration/injection eager injections', {
  setup() {
    Ember.MODEL_FACTORY_INJECTIONS = true;
    env = setupStore();

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/injection-test.js` at line 95

```js
  teardown() {
    // can be removed once we no longer support ember versions without lookupFactory
    Ember.MODEL_FACTORY_INJECTIONS = originalMODEL_FACTORY_INJECTIONS;

    run(env.store, 'destroy');
```

### Unknown Global

**Global**: `Ember.OrderedSet`

**Location**: `tests/integration/record-array-manager-test.js` at line 307

```js
  let record = {};
  let internalModel = {
    _recordArrays: new Ember.OrderedSet(),
    getRecord() {
      return record;
```

### Unknown Global

**Global**: `Ember.Registry`

**Location**: `tests/unit/model-test.js` at line 1001

```js

  let registry, container;
  if (Ember.Registry) {
    registry = new Ember.Registry();
    container = registry.container();
```

### Unknown Global

**Global**: `Ember.Registry`

**Location**: `tests/unit/model-test.js` at line 1002

```js
  let registry, container;
  if (Ember.Registry) {
    registry = new Ember.Registry();
    container = registry.container();
  } else {
```

### Unknown Global

**Global**: `Ember.Container`

**Location**: `tests/unit/model-test.js` at line 1005

```js
    container = registry.container();
  } else {
    container = new Ember.Container();
    registry = container;
  }
```

### Unknown Global

**Global**: `Ember.Registry`

**Location**: `tests/unit/model-test.js` at line 1035

```js

  let registry, container;
  if (Ember.Registry) {
    registry = new Ember.Registry();
    container = registry.container();
```

### Unknown Global

**Global**: `Ember.Registry`

**Location**: `tests/unit/model-test.js` at line 1036

```js
  let registry, container;
  if (Ember.Registry) {
    registry = new Ember.Registry();
    container = registry.container();
  } else {
```

### Unknown Global

**Global**: `Ember.Container`

**Location**: `tests/unit/model-test.js` at line 1039

```js
    container = registry.container();
  } else {
    container = new Ember.Container();
    registry = container;
  }
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/dummy/app/app.js` at line 9

```js
let App;

Ember.MODEL_FACTORY_INJECTIONS = true;

App = Application.extend({
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 16

```js

let env, store, User, Message, Post, Comment, Book, Chapter, Author, NewMessage;
const injectionValue = Ember.MODEL_FACTORY_INJECTIONS;

module("integration/relationship/belongs_to Belongs-To Relationships", {
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 543

```js
test("relationshipsByName is cached in production", function(assert) {
  let model = store.modelFor('user');
  let oldTesting = Ember.testing;
  //We set the cacheable to true because that is the default state for any CP and then assert that it
  //did not get dynamically changed when accessed
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 561

```js
test("relatedTypes is cached in production", function(assert) {
  let model = store.modelFor('user');
  let oldTesting = Ember.testing;
  //We set the cacheable to true because that is the default state for any CP and then assert that it
  //did not get dynamically changed when accessed
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 579

```js
test("relationships is cached in production", function(assert) {
  let model = store.modelFor('user');
  let oldTesting = Ember.testing;
  //We set the cacheable to true because that is the default state for any CP and then assert that it
  //did not get dynamically changed when accessed
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 16

```js

let env, store, User, Message, Post, Comment, Book, Chapter, Author, NewMessage;
const injectionValue = Ember.MODEL_FACTORY_INJECTIONS;

module("integration/relationship/belongs_to Belongs-To Relationships", {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 88

```js

  afterEach() {
    Ember.MODEL_FACTORY_INJECTIONS = injectionValue;
    run(env.container, 'destroy');
  }
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 543

```js
test("relationshipsByName is cached in production", function(assert) {
  let model = store.modelFor('user');
  let oldTesting = Ember.testing;
  //We set the cacheable to true because that is the default state for any CP and then assert that it
  //did not get dynamically changed when accessed
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 549

```js
  let oldCacheable = relationshipsByName._cacheable;
  relationshipsByName._cacheable = true;
  Ember.testing = false;
  try {
    assert.equal(get(model, 'relationshipsByName'), get(model, 'relationshipsByName'), 'relationshipsByName are cached');
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 554

```js
    assert.equal(get(model, 'relationshipsByName'), get(model, 'relationshipsByName'), 'relationshipsByName are cached');
  } finally {
    Ember.testing = oldTesting;
    relationshipsByName._cacheable = oldCacheable;
  }
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 561

```js
test("relatedTypes is cached in production", function(assert) {
  let model = store.modelFor('user');
  let oldTesting = Ember.testing;
  //We set the cacheable to true because that is the default state for any CP and then assert that it
  //did not get dynamically changed when accessed
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 567

```js
  let oldCacheable = relatedTypes._cacheable;
  relatedTypes._cacheable = true;
  Ember.testing = false;
  try {
    assert.equal(get(model, 'relatedTypes'), get(model, 'relatedTypes'), 'relatedTypes are cached');
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 572

```js
    assert.equal(get(model, 'relatedTypes'), get(model, 'relatedTypes'), 'relatedTypes are cached');
  } finally {
    Ember.testing = oldTesting;
    relatedTypes._cacheable = oldCacheable;
  }
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 579

```js
test("relationships is cached in production", function(assert) {
  let model = store.modelFor('user');
  let oldTesting = Ember.testing;
  //We set the cacheable to true because that is the default state for any CP and then assert that it
  //did not get dynamically changed when accessed
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 585

```js
  let oldCacheable = relationships._cacheable;
  relationships._cacheable = true;
  Ember.testing = false;
  try {
    assert.equal(get(model, 'relationships'), get(model, 'relationships'), 'relationships are cached');
```

### Unknown Global

**Global**: `Ember.testing`

**Location**: `tests/integration/relationships/belongs-to-test.js` at line 590

```js
    assert.equal(get(model, 'relationships'), get(model, 'relationships'), 'relationships are cached');
  } finally {
    Ember.testing = oldTesting;
    relationships._cacheable = oldCacheable;
  }
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/has-many-test.js` at line 1351

```js
  assert.expect(1);

  let injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/has-many-test.js` at line 1351

```js
  assert.expect(1);

  let injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/has-many-test.js` at line 1352

```js

  let injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

  try {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/has-many-test.js` at line 1364

```js
    });
  } finally {
    Ember.MODEL_FACTORY_INJECTIONS = injectionValue;
  }
});
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 159

```js
test("Setting the polymorphic belongsTo gets propagated to the inverse side - model injections true", function(assert) {
  assert.expect(2);
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 199

```js

testInDebug("Setting the polymorphic belongsTo with an object that does not implement the mixin errors out - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 159

```js
test("Setting the polymorphic belongsTo gets propagated to the inverse side - model injections true", function(assert) {
  assert.expect(2);
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 160

```js
  assert.expect(2);
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

  try {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 194

```js
    });
  } finally {
    Ember.MODEL_FACTORY_INJECTIONS = injectionValue;
  }
});
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 199

```js

testInDebug("Setting the polymorphic belongsTo with an object that does not implement the mixin errors out - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 200

```js
testInDebug("Setting the polymorphic belongsTo with an object that does not implement the mixin errors out - model injections true", function(assert) {
  var injectionValue = Ember.MODEL_FACTORY_INJECTIONS;
  Ember.MODEL_FACTORY_INJECTIONS = true;

  try {
```

### Unknown Global

**Global**: `Ember.MODEL_FACTORY_INJECTIONS`

**Location**: `tests/integration/relationships/polymorphic-mixins-belongs-to-test.js` at line 230

```js
    });
  } finally {
    Ember.MODEL_FACTORY_INJECTIONS = injectionValue;
  }
});
```
