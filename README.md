# rmodal-component

> in developing

[![NPM](https://img.shields.io/npm/v/rmodal-component.svg)](https://www.npmjs.com/package/rmodal-component) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Full Document
-   [Document](https://mostafarostami72.github.io/rmodal-component/)
## Demo
-   [Demo](https://mostafarostami72.github.io/rmodal-component/)


## Install

```bash
npm install --save rmodal-component
```

## Usage

```jsx
import React, {useState} from 'react';
import Modal from 'rmodal-component';

const Example = () => {
    const [show, setShow] = useState(false);
    
    return (
        <div>
            <Modal show={show} onClose={() => setShow(false)} smModal={true} modalTitle={"modal Title"}>
                ...
            </Modal>
        </div>
    );
};

export default Example;

```

## License

MIT © [MostafaRostami72](https://github.com/MostafaRostami72)
