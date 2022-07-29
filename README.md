# HRNet Modal

## Install

```bash
npm i modal-react-hrnet
```

## Usage

```jsx
import Modal from 'modal-react-hrnet';

function Example() {
  const [modalIsOpen, setModalIsOpen] = useState(false)

  return (
    <Modal
      setOpen={setModalIsOpen}
      message='Employee created'
      buttonText='Close'
    />
  )
}
```
