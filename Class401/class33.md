# Class 33 Reading: `<Login />` and `<Auth />`

## Resources

- [What is RBAC?](https://www.digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
- [React-Cookie Library](https://www.npmjs.com/package/react-cookie)
- [React-Cookies Component](https://www.npmjs.com/package/react-cookies)

## Topic 1

1. What is Role Based Access Control (RBAC)?

    - RBAC is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.

2. Share an example of RBAC including all possible CRUD operations and correlating roles:

    - Example: A company has a database with information about all of its employees. The database has a table for each department. The company has 3 departments: Sales, Marketing, and Engineering. The company has 3 roles: Manager, Supervisor, and Employee. The company has 3 users: Bob, Sally, and Joe. Bob is a Manager in the Sales department. Sally is a Supervisor in the Marketing department. Joe is an Employee in the Engineering department. Bob can read, create, update, and delete information in the Sales table. Sally can read, create, and update information in the Marketing table. Joe can only read information in the Engineering table.

3. What are the benefits of RBAC?

    - RBAC provides a number of benefits to an organization. In addition to the direct security benefits, RBAC can also provide indirect benefits by creating a more efficient, manageable environment that is less prone to error. The following are some of the benefits of RBAC:

        - Reducing administrative work and IT support.
        - Maximizing operational efficiency.
        - Improving compliance.
        - Improving security.
        - Reducing the likelihood of error.

## Compare/Contrast React Cookie Library vs. React Cookie Component

1. Describe some `react-cookie` library features:

    - `react-cookie` is a library that provides a simple, lightweight JavaScript API for handling browser cookies. `react-cookie` is an abstraction over the built-in `document.cookie` API. It makes cookies easier to use by providing a number of additional features:

        - Supports both server-side and client-side rendering.
        - Supports cookie expiration.
        - Supports cookie path and domain.
        - Supports cookie deletion.
        - Supports cookie serialization and deserialization.
        - Supports JSON cookies.
        - Supports automatic conversion between `Number` and `String` cookies.
        - Supports automatic conversion between `Boolean` and `String` cookies.
        - Supports automatic conversion between `Object` and `String` cookies.
        - Supports automatic conversion between `Array` and `String` cookies.
        - Supports automatic conversion between `Date` and `String` cookies.
        - Supports automatic conversion between `RegExp` and `String` cookies.
        - Supports automatic conversion between `Map` and `String` cookies.
        - Supports automatic conversion between `Set` and `String` cookies.
        - Supports automatic conversion between `Symbol` and `String` cookies.
        - Supports automatic conversion between `Function` and `String` cookies.
        - Supports automatic conversion between `undefined` and `String` cookies.
        - Supports automatic conversion between `null` and `String` cookies.
        - Supports automatic conversion between `NaN` and `String` cookies.
        - Supports automatic conversion between `Infinity` and `String` cookies.
        - Supports automatic conversion between `-Infinity` and `String` cookies.
        - Supports automatic conversion between `BigInt` and `String` cookies.
        - Supports automatic conversion between `BigInt64Array` and `String` cookies.
        - Supports automatic conversion between `BigUint64Array` and `String` cookies.
        - Supports automatic conversion between `ArrayBuffer` and `String` cookies.
        - Supports automatic conversion between `DataView` and `String` cookies.
        - Supports automatic conversion between `Int8Array` and `String` cookies.
        - Supports automatic conversion between `Uint8Array` and `String` cookies.
        - Supports automatic conversion between `Uint8ClampedArray` and `String` cookies.
        - Supports automatic conversion between `Int16Array` and `String` cookies.
        - Supports automatic conversion between `Uint16Array` and `String` cookies.

2. Describe some `react-cookies` component features:

    - `react-cookies` is a component that provides a simple, lightweight JavaScript API for handling browser cookies. `react-cookies` is an abstraction over the built-in `document.cookie` API. This component makes cookies easier to use by providing a number of additional features:

        - Supports both server-side and client-side rendering.
        - Supports cookie expiration.
        - Supports cookie path and domain.
        - Supports cookie deletion.
        - Supports cookie serialization and deserialization.
        - Supports JSON cookies.

3. Which library would you prefer would prefer? Why?

    - I would prefer `react-cookie` library because it is a library that provides a simple, lightweight JavaScript API for handling browser cookies. `react-cookie` is an abstraction over the built-in `document.cookie` API. It makes cookies easier to use and provides a number of additional features.

### Things I Want to Know More About

1. I would like to see better documentation describing the difference between the `react-cookie` library and the `react-cookies` component.

![GIF](https://media.giphy.com/media/bAlYQOugzX9sY/giphy.gif)
