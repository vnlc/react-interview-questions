**Đọc bằng ngôn ngữ khác: [English 🇺🇸](README.en.md),
[Polska 🇵🇱](README.pl.md), [German 🇩🇪](README.de.md), [French 🇫🇷](README.fr.md),
[Spanish 🇪🇸](README.es.md), [Українська 🇺🇦](README.md), [Tiếng Việt 🇻🇳](README.vi.md).**

<h1>
  React <img src="./assets/react.svg" width="40" height="40" />
</h1>

<h2>Những câu hỏi phỏng vấn React phổ biến nhất và câu trả lời</h2>

<details>
<summary>1. React là gì?</summary>

#### React

React là một thư viện JavaScript để xây dựng giao diện người dùng. Các đặc điểm chính:

1. **Kiến trúc component:** Giao diện được chia thành các component độc lập có thể tái sử dụng.

2. **Virtual DOM:** Đảm bảo cập nhật giao diện hiệu quả bằng cách giảm thiểu thao tác trên DOM thực.

3. **Tính khai báo:** Bạn mô tả giao diện trông như thế nào ở một trạng thái nhất định, và React giữ nó đồng bộ.

4. **Luồng dữ liệu một chiều:** Dữ liệu được truyền từ trên xuống qua props, giúp quản lý trạng thái dễ hơn.

React được tạo ra bởi Facebook và được sử dụng rộng rãi để phát triển SPA (Single Page Application).

</details>

<details>
<summary>2. Liệt kê các tính năng của React.</summary>

#### React

1. **Kiến trúc component:** Code được chia thành các component độc lập, có thể tái sử dụng.

2. **Virtual DOM:** Cập nhật giao diện nhanh mà không cần thao tác trực tiếp trên DOM.

3. **Luồng dữ liệu một chiều:** Dữ liệu được truyền từ component cha xuống component con qua props.

4. **JSX:** Một phần mở rộng cú pháp JavaScript để viết giao diện dạng XML.

5. **State và lifecycle:** Các component có thể lưu trữ và quản lý trạng thái riêng.

6. **React Hooks:** Thêm khả năng quản lý trạng thái và side effect cho functional component.

7. **Hệ sinh thái:** Hỗ trợ các thư viện như React Router và Redux để mở rộng chức năng.

8. **Thân thiện với SEO (với Next.js):** Server-side rendering cải thiện việc index.

9. **Phát triển mobile:** React Native cho phép xây dựng ứng dụng mobile dựa trên React.

10. **Mã nguồn mở:** Được cộng đồng hỗ trợ tích cực.

</details>

<details>
<summary>3. Các chức năng chính của React là gì?</summary>

#### React

#### Các chức năng chính của React:

1. **Phương pháp khai báo:** React cho phép bạn xây dựng giao diện tương tác bằng cách mô tả nó trông như thế nào, trong khi thư viện tối ưu hóa việc cập nhật DOM.

2. **Cấu trúc component:** Ứng dụng được xây dựng từ các component độc lập, có thể tái sử dụng, giúp đơn giản hóa việc phát triển, kiểm thử và bảo trì.

3. **Virtual DOM:** React sử dụng Virtual DOM để cập nhật DOM thực một cách hiệu quả, cải thiện đáng kể hiệu suất.

4. **Luồng dữ liệu một chiều:** Dữ liệu được truyền từ component cha xuống component con qua props, đơn giản hóa quản lý trạng thái.

5. **Hooks:** Cho phép sử dụng trạng thái và lifecycle trong functional component.

6. **JSX:** Phần mở rộng JavaScript để mô tả giao diện với cú pháp tương tự HTML.

7. **React Native:** Khả năng xây dựng ứng dụng mobile native sử dụng cùng nguyên tắc như web.

8. **Hệ sinh thái:** Bộ thư viện và công cụ lớn như React Router, Redux và Context API.

9. **Hỗ trợ Server-side rendering (SSR):** Giúp tối ưu SEO và tăng tốc tải trang ban đầu.

10. **Quản lý trạng thái:** Sử dụng `useState`, Context API, Redux hoặc các thư viện khác.

Những tính năng này làm cho React trở thành thư viện mạnh mẽ và linh hoạt để xây dựng ứng dụng hiện đại.

</details>

<details>
<summary>4. Những ưu điểm chính khi sử dụng React là gì?</summary>

#### React

#### Ưu điểm chính khi sử dụng React

1. **Tốc độ**: Nhờ Virtual DOM, React giảm thiểu tương tác với DOM thực, cải thiện hiệu suất.

2. **Kiến trúc component**: Code được chia thành các component tái sử dụng, đơn giản hóa phát triển và bảo trì.

3. **Luồng dữ liệu một chiều**: Dữ liệu trong React chảy một chiều (từ trên xuống), giúp debug dễ hơn.

4. **Cộng đồng lớn**: React có hệ sinh thái khổng lồ gồm thư viện, công cụ và extension.

5. **Tương thích với phát triển mobile**: Sử dụng React Native, bạn có thể xây dựng ứng dụng mobile đa nền tảng.

6. **JSX**: Cú pháp cho phép viết JavaScript cùng với markup giống HTML, cải thiện khả năng đọc code.

7. **Hỗ trợ Hooks**: Đơn giản hóa làm việc với trạng thái và lifecycle trong functional component.

8. **Thân thiện với SEO**: Server-side rendering với các công cụ như Next.js cải thiện SEO.

9. **Tính linh hoạt**: React có thể tích hợp vào bất kỳ dự án hoặc framework nào mà không cần thay đổi code đáng kể.

10. **React DevTools**: Công cụ debug tiện lợi để kiểm tra component và trạng thái ứng dụng.

</details>

<details>
<summary>5. JSX là gì?</summary>

#### React

**JSX (JavaScript XML)** là cú pháp cho phép bạn viết cấu trúc giao diện dạng XML bên trong JavaScript. JSX là phần mở rộng của JavaScript và được sử dụng trong React để mô tả giao diện trông như thế nào.

#### Các tính năng chính của JSX:

1. **Cú pháp giống XML:** Trông giống HTML nhưng được dùng trong JavaScript.

```jsx
const element = Hello, world!;
```

2. **JavaScript nhúng:** Bạn có thể viết code JavaScript bên trong dấu ngoặc nhọn `{}`.

```jsx
const name = 'Alice';
const element = Hello, {name}!;
```

3. **Biên dịch:** JSX được biên dịch thành JavaScript thông thường bằng các thư viện như Babel.

```jsx
const element = Hello;
// Trở thành:
const element = React.createElement('h1', null, 'Hello');
```

4. **Thuộc tính:** Được sử dụng tương tự HTML, nhưng thay vì `class` viết `className`, và thay vì `for` viết `htmlFor`.

```jsx
const input = ;
```

5. **JSX trả về cây phần tử:** Một biểu thức JSX chỉ có thể trả về một phần tử gốc. Dùng `<React.Fragment>` hoặc thẻ rỗng `<>` để nhóm.

```jsx
return <>Title Description</>;
```

#### Ưu điểm:

- Tạo UI component thuận tiện.
- Cú pháp rõ ràng và dễ đọc.
- Tích hợp chặt chẽ với logic JavaScript.

JSX không bắt buộc trong React, nhưng được sử dụng rộng rãi vì sự tiện lợi và linh hoạt.

</details>

<details>
<summary>6. Sự khác biệt giữa state và props là gì?</summary>

#### React

#### Sự khác biệt giữa state và props

| Tiêu chí             | State                                                       | Props                                                       |
| -------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- |
| **Mục đích**         | Lưu trữ trạng thái nội bộ của component.                   | Truyền dữ liệu từ component cha xuống component con.        |
| **Khả năng thay đổi** | Có thể thay đổi bên trong component.                       | Bất biến (chỉ đọc).                                        |
| **Phạm vi**          | Chỉ có trong component nơi nó được định nghĩa.             | Có sẵn trong component con qua thuộc tính.                  |
| **Khởi tạo**         | Được đặt bên trong component bằng `useState` hoặc constructor. | Được định nghĩa bởi component cha.                      |
| **Phạm vi sử dụng**  | Dùng để lưu dữ liệu động có thể thay đổi.                  | Dùng để truyền dữ liệu cố định hoặc động.                   |
| **Ai kiểm soát?**    | Component nơi trạng thái được định nghĩa.                   | Component cha.                                              |

</details>

<details>
<summary>7. Sự khác biệt giữa element và component là gì?</summary>

#### React

#### Sự khác biệt giữa element và component trong React:

| Tiêu chí            | Element                                                       | Component                                                                                          |
| ------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Định nghĩa**      | Một đối tượng mô tả giao diện trông như thế nào.              | Một hàm hoặc class trả về các React element.                                                       |
| **Loại**            | Bất biến.                                                     | Có thể tái sử dụng và có thể có trạng thái.                                                        |
| **Cú pháp tạo**     | `React.createElement` hoặc JSX (`<div />`).                  | Hàm hoặc class (`function MyComponent() {}` hoặc `class MyComponent extends React.Component {}`). |
| **Mục đích**        | Đại diện cho một node trong DOM.                              | Đóng gói logic và cấu trúc giao diện.                                                              |
| **Cách dùng**       | Dùng để tạo giao diện ở mức cơ bản.                           | Dùng để xây dựng cấu trúc phức tạp hơn với business logic.                                        |
| **Ví dụ**           | `<h1>Hello</h1>`                                              | `function Hello() { return <h1>Hello</h1>; }`                                                      |

Element là "khối xây dựng," trong khi component là "bộ tạo" để tạo ra giao diện phức tạp.

</details>

<details>
<summary>8. Làm thế nào để tạo component trong React?</summary>

#### React

#### Trong React, component có thể được tạo theo hai cách:

1. **Functional component:** Là một hàm đơn giản trả về các React element.

```jsx
function Greeting(props) {
  return Hello, {props.name}!;
}

// Cách dùng:
;
```

2. **Class component:** Là một class extends `React.Component` và phải có phương thức `render`.

```jsx
class Greeting extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Cách dùng:
;
```

#### Sự khác biệt:

- Functional component đơn giản hơn và phù hợp hơn cho các component không có trạng thái.

- Class component được dùng cho các component phức tạp hơn với trạng thái riêng hoặc lifecycle methods.

**Lưu ý:** Cách tiếp cận hiện đại là sử dụng functional component với hooks thay vì class component.

</details>

<details>
<summary>9. State trong React là gì?</summary>

#### React

**State** trong React là một đối tượng dùng để lưu dữ liệu có thể thay đổi theo thời gian và ảnh hưởng đến cách component được render. State cho phép React component trở nên động và phản hồi với các sự kiện, đầu vào người dùng và nhiều hơn nữa.

#### Đặc điểm của state:

1. **Cục bộ với component:** State chỉ có trong component nơi nó được định nghĩa.

2. **Thay đổi bất đồng bộ:** React gộp các lần gọi `setState` để tối ưu rendering.

3. **Được khởi tạo trong constructor** (với class component) hoặc với `useState` (trong functional component).

#### Trong class component:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        Count: {this.state.count}
        Increment

    );
  }
}
```

#### Trong functional component (với hook `useState`):

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (

      Count: {count}
      <button onClick={() => setCount(count + 1)}>Increment

  );
}
```

#### Sự khác biệt chính giữa state và props:

- **State** là cục bộ với component và có thể thay đổi.

- **Props** được truyền từ bên ngoài và bất biến.

</details>

<details>
<summary>10. Props trong React là gì?</summary>

#### React

**Props** trong React là một đối tượng chứa dữ liệu được truyền từ component cha xuống component con. Chúng được dùng để cấu hình component và bất biến.

#### Đặc điểm của props:

1. **Truyền từ trên xuống** (luồng dữ liệu một chiều) từ component cha xuống component con.

2. **Bất biến**: Component không thể thay đổi props mà nó nhận.

3. **Động**: Giá trị props có thể thay đổi nếu dữ liệu trong component cha thay đổi.

#### Sử dụng props:

1. **Trong functional component:**

```jsx
function Welcome(props) {
  return Hello, {props.name}!;
}

// Cách dùng:
;
```

2. **Trong class component:**

```jsx
class Welcome extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Cách dùng:
;
```

#### Truyền props:

```jsx
function App() {
  return (

  );
}
```

**Kết quả:**

```bash
Hello, Alice!
Hello, Bob!
```

#### Destructuring props:

```jsx
function Welcome({ name }) {
  return Hello, {name}!;
}
```

#### Giá trị mặc định của props:

```jsx
function Welcome({ name = 'Guest' }) {
  return Hello, {name}!;
}

// Cách dùng:
; // Xuất ra: Hello, Guest!
```

Props cung cấp sự linh hoạt và khả năng tái sử dụng cho React component.

</details>

<details>
<summary>11. Tại sao cần thuộc tính `key` khi render danh sách?</summary>

#### React

Thuộc tính `key` được dùng để xác định các phần tử trong danh sách khi render.

#### Mục đích:

1. **_Tối ưu hóa cập nhật:_** React dùng `key` để cập nhật giao diện hiệu quả bằng cách xác định nhanh các phần tử cần thay đổi, thêm hoặc xóa.

2. **_Ngăn render không cần thiết:_** `key` giúp tránh render lại các phần tử không thay đổi.

3. **_Bảo toàn trạng thái component:_** Ví dụ, nếu một mục danh sách chứa form, `key` cho phép React bảo toàn trạng thái của nó giữa các lần cập nhật.

#### Cách dùng đúng:

- Giá trị `key` phải là duy nhất trong các phần tử cùng cấp.

- Các định danh ổn định hoạt động tốt nhất (ví dụ: `id` từ database).

- Không nên dùng chỉ số mảng làm `key`, vì điều này có thể gây lỗi khi thứ tự phần tử thay đổi.

```jsx
const items = ['Apple', 'Banana', 'Cherry'];
return (

    {items.map((item, index) => (
      {item} // Key duy nhất cho mỗi phần tử
    ))}

);
```

</details>

<details>
<summary>12. Dữ liệu được truyền giữa các component trong React như thế nào?</summary>

#### React

Trong React, dữ liệu được truyền giữa các component theo phân cấp như sau:

#### Truyền dữ liệu xuống (từ cha xuống con)

Props được dùng để truyền dữ liệu xuống. Component cha truyền giá trị hoặc hàm cho component con qua thuộc tính.

**Ví dụ:**

```jsx
function ParentComponent() {
  const data = 'Hello from Parent';

  return;
}

function ChildComponent({ message }) {
  return { message };
}
```

`message` truyền giá trị `data` cho component con `ChildComponent`.

Trong component con, props được truy cập qua tham số hàm hoặc qua `this.props` trong class component.

#### Truyền dữ liệu lên (từ con lên cha)

Dữ liệu được truyền lên bằng hàm callback. Component cha truyền một hàm cho con, và con gọi nó với dữ liệu cần thiết.

**Ví dụ:**

```jsx
function ParentComponent() {
  const handleData = childData => {
    console.log('Data from child:', childData);
  };

  return ;
}

function ChildComponent({ sendData }) {
  const data = 'Hello from Child';

  return <button onClick={() => sendData(data)}>Send Data;
}
```

Component cha truyền hàm `handleData` trong prop `sendData`.

Component con gọi `sendData`, truyền giá trị `data`.

#### Các cách tiếp cận thay thế cho ứng dụng phức tạp:

1. **Context (Context API):**

Dùng để truyền dữ liệu sâu qua phân cấp mà không cần props.

Phù hợp cho trạng thái toàn cục, như theme hoặc ngôn ngữ giao diện.

```jsx
const MyContext = React.createContext();

function ParentComponent() {
  const data = 'Hello from Context';

  return (

  );
}

function ChildComponent() {
  const contextData = React.useContext(MyContext);

  return {contextData};
}
```

2. **State manager (Redux, Zustand, MobX):** Để truyền dữ liệu trong ứng dụng lớn qua một trạng thái toàn cục duy nhất.

3. **Custom Hooks:** Dùng để chia sẻ logic giữa các component.

</details>

<details>
<summary>13. Tại sao React dùng `className` thay vì thuộc tính `class`?</summary>

#### React

React dùng `className` thay vì `class` vì `class` là từ khóa dành riêng trong JavaScript.

#### Lý do:

1. **Tránh xung đột**: `class` được dùng để định nghĩa class trong JavaScript (`class MyComponent {}`), có thể gây lỗi cú pháp.

2. **Tương thích JSX**: JSX là phần mở rộng cú pháp của JavaScript, nên dùng `className` tránh nhầm lẫn.

3. **Ánh xạ trực tiếp** trong `document.createElement`: React chuyển đổi JSX thành lời gọi `React.createElement`, và `className` được dùng để đặt class cho các phần tử DOM.

#### Ví dụ:

```jsx
// Đúng trong React

Hello;

// Sai (lỗi cú pháp)

Hello;
```

Đây là tiêu chuẩn của React đảm bảo tính ổn định và nhất quán trong code.

</details>

<details>
<summary>14. Những quy tắc đặt tên và ngoại lệ nào tồn tại cho React component?</summary>

#### React

Trong React, có một số quy tắc và ngoại lệ quan trọng về tên component:

1. **Chữ hoa cho component:** Tên component phải bắt đầu bằng chữ hoa. Điều này cần thiết để React phân biệt component với các phần tử HTML tiêu chuẩn.

Ví dụ:

- Đúng: `<MyComponent />`
- Sai: `<myComponent />`

2. **CamelCase:** Nên dùng CamelCase cho tên component. Điều này có nghĩa là mỗi từ mới trong tên component bắt đầu bằng chữ hoa:

- `MyComponent`
- `UserProfile`

3. **Tên không trùng với phần tử HTML:** Không dùng tên component trùng với các thẻ HTML tiêu chuẩn như `div`, `span`, `button`, v.v. Điều này có thể gây xung đột và hành vi không mong muốn:

- Đúng: `<CustomButton />`
- Sai: `<button />` (mặc dù đây là phần tử HTML, trong React nó sẽ được coi là thẻ HTML tiêu chuẩn)

4. **Tránh ký tự đặc biệt:** Không dùng ký tự đặc biệt trong tên component (ví dụ: khoảng trắng, dấu gạch ngang, gạch dưới, v.v.):

- Đúng: `MyComponent`
- Sai: `my_component`, `my-component`

5. **Functional component vs. class:** Nếu dùng class cho component, chúng cũng phải có tên bắt đầu bằng chữ hoa:

- `class MyComponent extends React.Component {}`

Tuân theo các quy tắc này giúp đảm bảo hành vi đúng và rõ ràng trong code.

</details>

<details>
<summary>15. Làm thế nào để viết comment trong React?</summary>

#### React

Trong React, comment được viết giống như trong JavaScript, nhưng có một số điểm khác biệt khi dùng trong JSX.

1. **Comment trong JavaScript (bên ngoài JSX)**

```javascript
// Comment một dòng

/*
Comment nhiều dòng
*/
```

2. **Comment bên trong JSX**

- Trong JSX, bạn cần dùng cú pháp đặc biệt vì JSX là một phần của JavaScript.

- Comment trong JSX phải được viết bên trong dấu ngoặc nhọn `{}`:

```jsx
function MyComponent() {
  return (

      {/_ Đây là comment bên trong JSX _/}
      Hello, world!

  );
}
```

- Comment trong JSX phải được bọc trong `{/* comment */}`, nếu không sẽ gây lỗi.

- Chúng chỉ có thể dùng bên trong biểu thức JSX.

3. **Comment trong hàm và phương thức**

- Đối với comment bên trong hàm hoặc phương thức, bạn có thể dùng comment JavaScript tiêu chuẩn:

```jsx
function MyComponent() {
  // Đây là nơi chúng ta render component
  return Hello, world!;
}
```

#### Tóm tắt:

- Trong JSX, dùng `{/* comment */}`.

- Trong JavaScript thông thường, dùng `//` cho comment một dòng và `/* ... */` cho comment nhiều dòng.

</details>

<details>
<summary>16. Virtual DOM trong React là gì?</summary>

#### React

**Virtual DOM** là biểu diễn ảo của DOM thực mà React sử dụng để cập nhật giao diện hiệu quả.

#### Cách hoạt động trong React:

1. **Render vào Virtual DOM:** Khi trạng thái hoặc props của component thay đổi, React cập nhật Virtual DOM.

2. **Diffing:** React so sánh Virtual DOM mới với phiên bản cũ, xác định tập hợp thay đổi tối thiểu.

3. **Cập nhật DOM thực:** Các thay đổi được phát hiện được áp dụng lên DOM thực, giảm thiểu số lượng thao tác.

#### Ưu điểm chính:

Tối ưu hóa cập nhật DOM, cải thiện đáng kể hiệu suất ứng dụng.

</details>

<details>
<summary>17. Prop `key` là gì và lợi ích của nó khi dùng trong mảng phần tử?</summary>

#### React

Trong React, prop `key` được dùng để xác định mỗi phần tử trong danh sách hoặc mảng, giúp React quản lý render hiệu quả khi các mục danh sách thay đổi hoặc được cập nhật.

#### Các điểm quan trọng về `key`:

1. **Tính duy nhất:** Mỗi phần tử trong danh sách phải có `key` duy nhất. Điều này cho phép React theo dõi phần tử nào đang thay đổi, được thêm vào hoặc bị xóa, đồng thời bảo toàn trạng thái của chúng giữa các lần render.

2. **Tối ưu hóa render:** Dùng `key` cho phép React giảm số lần render lại bằng cách chỉ thực hiện các thay đổi cần thiết lên DOM. Không có `key`, React khó theo dõi thay đổi hơn, có thể dẫn đến render lại toàn bộ danh sách kể cả khi chỉ một mục thay đổi.

3. **Bản chất của `key`:** Prop `key` không được truyền vào component, nên không thể dùng để hiển thị giá trị trong giao diện. Đây là thuộc tính nội bộ chỉ React dùng để theo dõi phần tử.

#### Ví dụ dùng `key` trong danh sách:

```jsx
const items = ['apple', 'banana', 'cherry'];

function FruitList() {
  return (

      {items.map((item, index) => (
        {item} // Quan trọng: dùng key duy nhất
      ))}

  );
}
```

#### Tầm quan trọng của tính duy nhất của `key`:

- **Cách dùng sai:** Nếu dùng các giá trị không duy nhất làm key (ví dụ: cùng một index), React sẽ không theo dõi thay đổi đúng, dẫn đến lỗi render.

- **Key lý tưởng:** Thường nếu có định danh duy nhất cho phần tử (ví dụ: id), nên dùng nó làm key thay vì index mảng.

```jsx
const items = [
  { id: 1, name: 'apple' },
  { id: 2, name: 'banana' },
  { id: 3, name: 'cherry' },
];

function FruitList() {
  return (

      {items.map(item => (
        {item.name} // Tốt hơn là dùng id duy nhất
      ))}

  );
}
```

#### Lợi ích khi dùng `key`:

- Cải thiện hiệu suất render.

- Cho phép React chỉ cập nhật tối ưu các phần tử đã thay đổi thay vì toàn bộ danh sách.

- Đảm bảo xử lý đúng trạng thái phần tử khi các mục bị di chuyển, xóa hoặc cập nhật.

</details>

<details>
<summary>18. Conditional rendering trong React là gì?</summary>

#### React

Conditional rendering trong React là quá trình component render nội dung khác nhau tùy thuộc vào điều kiện nhất định. Điều này cho phép thay đổi động những gì component hiển thị dựa trên trạng thái, props hoặc các yếu tố khác.

#### Các cách tiếp cận chính để conditional rendering:

1. **Toán tử `if`:** Bạn có thể dùng toán tử `if` tiêu chuẩn để quyết định render gì.

```jsx
function Greeting(props) {
  if (props.isLoggedIn) {
    return Welcome back!;
  }
  return Please sign up.;
}
```

2. **Toán tử ternary:** Toán tử ternary thường được dùng cho biểu thức điều kiện ngắn hơn.

```jsx
function Greeting(props) {
  return {props.isLoggedIn ? 'Welcome back!' : 'Please sign up.'};
}
```

3. **Toán tử AND logic (`&&`) để render:** Bạn có thể dùng toán tử `&&` để render một phần tử chỉ khi biểu thức bên trái là truthy.

```jsx
function Notifications(props) {
  return (

      {props.unreadMessages.length > 0 && (
        You have {props.unreadMessages.length} unread messages.
      )}

  );
}
```

4. **Dùng `return` với toán tử điều kiện:** Bạn có thể dùng `return` cho conditional rendering dựa trên các điều kiện khác nhau, như trong ví dụ với `if` hoặc toán tử ternary.

#### Ưu điểm của conditional rendering:

- Cho phép nội dung thay đổi động tùy thuộc vào trạng thái hoặc props.

- Cải thiện tính linh hoạt và khả năng hiển thị nội dung khác nhau cho người dùng hoặc tình huống khác nhau.

#### Ví dụ:

```jsx
function UserStatus(props) {
  return (

      {props.isLoggedIn ? (
        Log Out
      ) : (
        Log In
      )}

  );
}
```

Ở đây nút thay đổi tùy thuộc vào việc người dùng đã đăng nhập hay chưa.

</details>

<details>
<summary>19. Fragment trong React là gì?</summary>

#### React

Fragment trong React là cách nhóm nhiều phần tử mà không thêm phần tử phụ vào DOM. Chúng cho phép trả về nhiều phần tử từ một component mà không cần wrapper như `div`, giúp tránh các phần tử không cần thiết có thể làm hỏng styles hoặc cấu trúc tài liệu.

#### Fragment được dùng như thế nào?

1. **Không có Fragment (với wrapper):**

```jsx
function MyComponent() {
  return (

      Title
      Some text

  );
}
```

Trong ví dụ này, một `div` duy nhất bọc `h1` và `p` được trả về.

2. **Với Fragment (không có wrapper):**

```jsx
function MyComponent() {
  return <>Title Some text</>;
}
```

Bây giờ `h1` và `p` được render mà không có container thêm, giúp giữ DOM sạch.

#### Ưu điểm:

- **DOM sạch:** Bạn có thể tránh các wrapper không cần thiết trong DOM.

- **Tiện cho render nhiều phần tử:** Bạn có thể trả về nhiều phần tử từ một component mà không cần wrapper thêm.

#### Cú pháp:

- Bạn có thể dùng thẻ rỗng `<>` và `</>`, là viết tắt của `<React.Fragment></React.Fragment>`.

- Bạn cũng có thể dùng `React.Fragment` nếu cần thêm key (ví dụ khi render danh sách):

```jsx
{
  item.name;
}
{
  item.description;
}
```

#### Khi nào nên dùng:

- Khi cần render nhiều phần tử mà không có wrapper thêm trong DOM.

- Khi muốn bảo toàn cấu trúc component mà không ảnh hưởng đến styles hoặc layout.

Fragment rất hữu ích để giảm các phần tử DOM không cần thiết và cải thiện hiệu suất.

</details>

<details>
<summary>20. Reconciliation là gì?</summary>

#### React

**Reconciliation** là quá trình React dùng để cập nhật DOM theo cách hiệu quả nhất. Khi trạng thái hoặc props của component thay đổi, React tính toán các thay đổi tối thiểu cần thực hiện trên DOM thực để đồng bộ hóa với trạng thái của virtual DOM.

#### Reconciliation hoạt động như thế nào?

1. **So sánh virtual DOM cũ và mới:**

- React giữ bản sao của virtual DOM trước đó.
- Khi trạng thái hoặc props thay đổi, virtual DOM mới được tạo ra.
- React so sánh virtual DOM mới với bản sao trước đó (thuật toán diffing).

2. **Phát hiện sự khác biệt (diffing):**

- React xác định những phần nào của cây đã thay đổi (phần tử mới, thay đổi thuộc tính hoặc xóa phần tử).
- Để làm điều này, nó dùng thuật toán được tối ưu hóa cho cấu trúc dạng cây.

3. **Cập nhật DOM thực:**

- React chỉ áp dụng thay đổi cho các phần DOM cần cập nhật, tránh render lại toàn bộ.

#### Nguyên tắc chính của reconciliation:

- **Bảo toàn các node cùng cấp:** Nếu các node có cùng kiểu (ví dụ: `<div>` vẫn là `<div>`), React chỉ thay đổi thuộc tính và phần tử con.
- **Tái sử dụng component:** Nếu component vẫn giữ nguyên, React tái sử dụng instance component hiện có.
- **Key cho danh sách:** Nếu danh sách phần tử được render từ mảng, React dùng key (prop `key`) để so sánh và bảo toàn các node.

#### Ví dụ:

```jsx
function App({ isVisible }) {
  return isVisible ? Hello : Goodbye;
}
```

- Nếu `isVisible` thay đổi từ `true` thành `false`, React sẽ xóa `<h1>` và thay thế bằng `<p>`.

#### Tầm quan trọng của key (prop `key`) cho danh sách:

Key giúp React xác định đúng các thay đổi trong danh sách. Ví dụ:

```jsx

  {items.map(item => (
    {item.text}
  ))}

```

Không có key duy nhất, React sẽ không thể xác định chính xác phần tử danh sách nào đã thay đổi.

#### Ưu điểm của reconciliation:

- Giảm số lượng thao tác DOM.
- Cải thiện hiệu suất ứng dụng.
- Cung cấp cập nhật giao diện mượt mà.

</details>

<details>
<summary>21. Làm thế nào để cập nhật trạng thái của component?</summary>

#### React

Trong React, trạng thái component được cập nhật bằng phương thức `setState` trong class component hoặc `useState` trong functional component.

#### Class component:

Trạng thái được cập nhật qua `this.setState()`.

#### Ví dụ:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        Count: {this.state.count}
        Increment

    );
  }
}
```

#### Functional component:

Trạng thái được cập nhật qua hàm trả về bởi `useState`.

#### Ví dụ:

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(count + 1);
  };

  return (

      Count: {count}
      Increment

  );
}
```

#### Lưu ý:

1. **Bất đồng bộ:** `setState` và `useState` hoạt động bất đồng bộ. Để cập nhật trạng thái dựa trên giá trị trước đó, dùng cách tiếp cận hàm:

```jsx
this.setState(prevState => ({ count: prevState.count + 1 }));
setCount(prevCount => prevCount + 1);
```

2. **Không cập nhật trạng thái trực tiếp:** Sửa đổi trạng thái mà không dùng `setState` hoặc `useState` không kích hoạt render lại.

</details>

<details>
<summary>22. Inline conditional expression là gì?</summary>

#### React

**Inline conditional expression** trong JavaScript (bao gồm React) là các cơ chế cho phép nhúng điều kiện trực tiếp vào JSX để render có điều kiện các phần tử hoặc component. Điều này làm cho code ngắn gọn và dễ hiểu hơn.

#### Các phương pháp chính:

1. **Toán tử điều kiện (toán tử ternary):** Đây là một trong những cách phổ biến nhất để render có điều kiện trong JSX.

```jsx
condition ? expression_if_true : expression_if_false;
```

**Ví dụ:**

```jsx
const isLoggedIn = true;

function App() {
  return {isLoggedIn ? 'Welcome, User!' : 'Please log in'};
}
```

2. **Toán tử AND logic (`&&`):** Phương pháp này cho phép hiển thị component hoặc phần tử chỉ khi điều kiện là `true`. Nếu điều kiện không thỏa, không có gì được render.

**Ví dụ:**

```jsx
const isUserAdmin = true;

function App() {
  return {isUserAdmin && You have admin privileges};
}
```

Trong trường hợp này, `<p>You have admin privileges</p>` chỉ hiển thị nếu `isUserAdmin` là `true`.

3. **`if` trước khi trả về JSX:** Bạn cũng có thể dùng câu lệnh `if` thông thường trước khi trả về JSX khi điều kiện phức tạp hơn.

**Ví dụ:**

```jsx
function App() {
  let content;
  if (isLoggedIn) {
    content = Welcome back!;
  } else {
    content = Please sign in.;
  }

  return {content};
}
```

**Ưu điểm:**

- Inline conditional expression cho phép viết code sạch và ngắn gọn hơn.

- Chúng cải thiện khả năng đọc và giảm nhu cầu cho các cấu trúc điều kiện phụ.

#### Quan trọng:

- Trong React, bạn không thể dùng câu lệnh `if` trực tiếp bên trong JSX. Tuy nhiên, bạn có thể dùng chúng trước khi trả về JSX.

</details>

<details>
<summary>23. Sự khác biệt giữa xử lý sự kiện trong HTML và React là gì?</summary>

#### React

#### Sự khác biệt giữa xử lý sự kiện trong HTML và React:

| Tiêu chí                   | HTML                                                             | React                                                                       |
| -------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------------- |
| **Gắn sự kiện**            | Được chỉ định là thuộc tính: `<button onclick="handler()">`.    | Dùng camelCase: `<button onClick={handler}>`.                               |
| **Loại hàm**               | Tham chiếu đến hàm toàn cục hoặc chuỗi có code JavaScript.      | Gắn với hàm component (thường là phương thức hoặc arrow function).          |
| **Thêm event listener**    | Handler được thêm thủ công qua `addEventListener`.               | React tự động quản lý binding qua virtual DOM.                              |
| **Context `this`**         | Context phải được đặt thủ công nếu dùng trong class.            | React bảo toàn context đúng tự động trong functional component.             |
| **Hành vi mặc định**       | Phải gọi `return false` để dừng hành vi.                        | Dùng `event.preventDefault()` để dừng hành vi mặc định.                     |
| **Tương thích**            | Chỉ xử lý sự kiện DOM thực.                                     | Dùng `SyntheticEvent`, là wrapper trên các sự kiện native.                  |
| **Hỗ trợ cross-browser**   | Phải xử lý thủ công sự khác biệt giữa các browser.              | React cung cấp tương thích cross-browser qua `SyntheticEvent`.              |
| **Binding context**        | Thường cần dùng `bind`.                                          | `bind` cần trong class component nhưng không cần trong functional.          |

#### Ví dụ trong HTML:

```html
Click me
```

#### Ví dụ trong React:

```jsx
function handleClick() {
  alert('Clicked!');
}

function App() {
  return Click me;
}
```

#### SyntheticEvent trong React:

React dùng wrapper trên các sự kiện native để chuẩn hóa hành vi trên các browser khác nhau và cải thiện hiệu suất.

</details>

<details>
<summary>24. Synthetic event trong React là gì?</summary>

#### React

**Synthetic event** trong React là wrapper bao quanh các sự kiện DOM native cung cấp giao diện nhất quán để xử lý sự kiện trên các browser khác nhau. React tạo ra `SyntheticEvent` cho mỗi sự kiện, cho phép xử lý sự kiện theo cách thống nhất, đảm bảo tương thích cross-browser và cải thiện hiệu suất.

#### Đặc điểm chính:

1. **Tương thích cross-browser:** `SyntheticEvent` trừu tượng hóa hành vi sự kiện đặc thù của browser và cung cấp hành vi nhất quán.

2. **Tối ưu hóa:** `SyntheticEvent` dùng object pooling giúp giảm chi phí tạo đối tượng sự kiện mới.

3. **Dùng một lần:** Sau khi sự kiện được xử lý, đối tượng `SyntheticEvent` được "trả lại" pool và không thể dùng sau đó. Đối với thao tác bất đồng bộ, sự kiện nên được lưu vào biến riêng.

4. **Giao diện:** `SyntheticEvent` có cùng phương thức với sự kiện native tiêu chuẩn (ví dụ: `preventDefault()` và `stopPropagation()`).

#### Ví dụ:

```jsx
function handleClick(event) {
  // SyntheticEvent cung cấp quyền truy cập phương thức preventDefault()
  event.preventDefault();
  console.log('Button clicked!');
}

function App() {
  return Click me;
}
```

Trong ví dụ này, `event` là `SyntheticEvent` hoạt động tương tự sự kiện native nhưng với khả năng cải tiến.

</details>

<details>
<summary>25. Làm thế nào để xử lý sự kiện trong React?</summary>

#### React

Trong React, xử lý sự kiện hoạt động tương tự JavaScript tiêu chuẩn, nhưng có một số điểm khác biệt. Các sự kiện trong React là synthetic, nghĩa là chúng cung cấp abstraction trên các sự kiện browser thực và đảm bảo tương thích cross-browser.

#### Nguyên tắc chính xử lý sự kiện trong React:

1. **Synthetic event:** Tất cả sự kiện trong React được bọc trong đối tượng **SyntheticEvent**, là implementation cross-browser của các sự kiện DOM tiêu chuẩn.

2. **Dùng camelCase cho sự kiện:** Trong React, sự kiện được viết theo camelCase thay vì chữ thường (ví dụ: `onClick` thay vì `onclick`).

3. **Truyền hàm làm event handler:** Sự kiện trong React được xử lý bằng hàm truyền qua thuộc tính component.

#### Ví dụ xử lý sự kiện `click`:

```jsx
import React, { Component } from 'react';

class MyButton extends Component {
  handleClick = () => {
    alert('Button clicked!');
  };

  render() {
    return Click Me;
  }
}

export default MyButton;
```

#### Ví dụ với functional component:

```jsx
import React, { useState } from 'react';

function MyButton() {
  const [count, setCount] = useState(0);

  const handleClick = () => {
    setCount(count + 1);
  };

  return Clicked {count} times;
}

export default MyButton;
```

#### Đặc điểm xử lý sự kiện:

1. **Không cần dùng `addEventListener`:** Trong React, không cần thêm hoặc xóa event handler thủ công. Điều này được quản lý tự động bởi thư viện React.

2. **Bảo toàn context trong phương thức class component:** Nếu phương thức class component được dùng làm event handler, context `this` phải được bind bằng arrow function hoặc thủ công trong constructor.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
    // Binding phương thức
    this.handleClick = this.handleClick.bind(this);
  }

  handleClick() {
    this.setState({ count: this.state.count + 1 });
  }

  render() {
    return (

        Clicked {this.state.count} times

    );
  }
}
```

3. **Truyền tham số cho hàm handler:** Nếu cần truyền thêm đối số cho event handler, bạn có thể dùng arrow function hoặc hàm có tham số.

```jsx
function MyButton({ label }) {
  const handleClick = (event, label) => {
    console.log(label);
  };

  return <button onClick={event => handleClick(event, label)}>{label};
}
```

#### Xử lý sự kiện trong DOM:

Tất cả sự kiện trong React hoạt động theo nguyên tắc event delegation, trong đó một event handler được đăng ký cho toàn bộ cây component và được định tuyến qua React `SyntheticEvent`.

</details>

<details>
<summary>26. Pointer Event là gì?</summary>

#### React

#### Pointer Event trong React

**Pointer Event** là API thống nhất các sự kiện chuột, cảm ứng và bút stylus thành một hệ thống xử lý sự kiện duy nhất.

#### Các Pointer Event chính

| **Sự kiện**         | **Mô tả**                                                                |
| ------------------- | ------------------------------------------------------------------------ |
| **onPointerDown**   | Kích hoạt khi nhấn bằng ngón tay, chuột hoặc bút stylus.                |
| **onPointerUp**     | Kích hoạt khi thả nút chuột, ngón tay hoặc bút stylus.                  |
| **onPointerMove**   | Kích hoạt khi con trỏ di chuyển trên phần tử.                           |
| **onPointerEnter**  | Kích hoạt khi con trỏ vào trong phạm vi phần tử.                        |
| **onPointerLeave**  | Kích hoạt khi con trỏ rời khỏi phạm vi phần tử.                         |
| **onPointerCancel** | Kích hoạt khi browser hủy sự kiện (ví dụ: khi thay đổi focus).          |

#### Ví dụ trong React

```jsx
const PointerExample = () => {
  const handlePointerDown = () => console.log('Pointer pressed');

  return (

      Click here

  );
};
```

Code này sẽ log `"Pointer pressed"` vào console khi nhấn bằng bất kỳ thiết bị nào (chuột, cảm ứng hoặc bút stylus).

</details>

<details>
<summary>27. Khi nào nên dùng class component thay vì functional component?</summary>

#### React

Class component từng được dùng khi cần một hoặc nhiều tính năng sau:

1. **Làm việc với state:** Trước đây, functional component không hỗ trợ local state, nên class được dùng cho mục đích này. Ngày nay, hook (`useState`, `useReducer`) cho phép functional component làm việc với state.

2. **Lifecycle method:** Class cung cấp quyền truy cập các phương thức như `componentDidMount`, `componentDidUpdate` và `componentWillUnmount` để quản lý component ở các giai đoạn khác nhau. Ngày nay, điều này được xử lý bởi hook `useEffect`.

3. **Xử lý logic phức tạp:** Nếu logic cần nhiều phương thức và truy cập thuộc tính qua `this`, class có vẻ là lựa chọn logic. Cách tiếp cận hiện đại là hook, cho phép đóng gói logic.

#### Khi class không còn cần thiết:

Bắt đầu từ React 16.8, functional component với hook thay thế nhu cầu cho class component. Vì vậy, trong các dự án mới, nên ưu tiên functional component. Class chủ yếu được dùng để duy trì legacy code.

</details>

<details>
<summary>28. Stateless component là gì?</summary>

#### React

Stateless component là các component không lưu trữ hoặc quản lý bất kỳ internal state nào. Chúng chỉ nhận dữ liệu qua props và hiển thị nó dưới dạng giao diện. Thường thì các component này là functional.

#### Đặc điểm:

1. **Không có state:** Chúng không dùng `this.state` và không thay đổi internal state.

2. **Chỉ render:** Chúng đơn giản nhận props và hiển thị chúng dưới dạng UI element.

3. **Đơn giản và dễ dự đoán:** Dễ kiểm thử và bảo trì hơn vì không cần theo dõi thay đổi trạng thái.

#### Ví dụ:

```jsx
// Stateless component
function Greeting(props) {
  return Hello, {props.name}!;
}

// Cách dùng:
;
```

#### Ưu điểm:

- **Đơn giản:** Dễ hiểu và bảo trì.

- **Tối ưu hiệu suất:** Vì các component này không có state, React có thể cập nhật chúng hiệu quả hơn.

#### Khi nào nên dùng:

- Khi component đơn giản chỉ hiển thị dữ liệu và không cần thay đổi.

</details>

<details>
<summary>29. Stateful component là gì?</summary>

#### React

**Stateful component** là các component lưu trữ và quản lý internal state. Chúng dùng state để lưu dữ liệu có thể thay đổi theo thời gian, và những thay đổi này ảnh hưởng đến việc render component.

#### Đặc điểm:

1. **State:** Chúng dùng `this.state` để lưu và quản lý dữ liệu có thể thay đổi.

2. **Phương thức cập nhật state:** Chúng dùng phương thức `this.setState()` để cập nhật state.

3. **Lifecycle:** Chúng có quyền truy cập các lifecycle method như `componentDidMount()`, `shouldComponentUpdate()`, `componentDidUpdate()`, v.v.

#### Ví dụ:

```jsx
// Stateful component
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      count: 0,
    };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        {this.state.count}
        Increment

    );
  }
}
```

#### Ưu điểm:

- **Component động:** Chúng có thể thay đổi nội dung và giao diện dựa trên thay đổi trạng thái.

- **Tương tác:** Phù hợp để xây dựng giao diện tương tác nơi state cần được cập nhật để phản hồi tương tác người dùng.

#### Khi nào nên dùng:

Khi component cần quản lý internal state, ví dụ để lưu đầu vào form, bộ đếm, lựa chọn, v.v.

</details>

<details>
<summary>30. Pure Component là gì?</summary>

#### React

**Pure Component** là các React class component đặc biệt tự động tối ưu hóa render. Chúng thực hiện so sánh shallow của props và state để ngăn các cập nhật không cần thiết nếu giá trị props hoặc state không thay đổi.

#### Làm thế nào để tạo Pure Component?

Pure Component được tạo bằng cách extends `React.PureComponent`.

```jsx
import React, { PureComponent } from 'react';

class MyComponent extends PureComponent {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Cách dùng:
;
```

#### `PureComponent` hoạt động như thế nào?

- Nó thực hiện so sánh shallow của props và state trong phương thức `shouldComponentUpdate`.

- Nếu props và state không thay đổi, component không render lại.

#### Khi nào nên dùng `PureComponent`?

- Khi props và state là các cấu trúc đơn giản (giá trị primitive hoặc đối tượng shallow).

- Để cải thiện hiệu suất trong các component cập nhật thường xuyên.

#### Hạn chế:

1. **So sánh sâu:** `PureComponent` không tính đến thay đổi bên trong đối tượng hoặc mảng lồng nhau. Ví dụ, nếu bạn cập nhật đối tượng nhưng tham chiếu vẫn không thay đổi, component sẽ không cập nhật.

```jsx
this.setState({ data: { ...this.state.data, key: 'new value' } }); // Cách giải quyết
```

2. **Không hoạt động với functional component:** Thay thế là dùng `React.memo` để tối ưu functional component.

```jsx
const MyComponent = React.memo(function MyComponent(props) {
  return Hello, {props.name}!;
});
```

</details>

<details>
<summary>31. Higher-Order Component (HOC) là gì?</summary>

#### React

**Higher-Order Component** là một hàm nhận component làm đối số đầu vào và trả về component mới, mở rộng chức năng của nó.

#### Cú pháp HOC:

```jsx
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

#### Đặc điểm HOC:

1. **Nhận component làm đối số.**
2. **Trả về component mới với props hoặc hành vi bổ sung.**
3. **Cho phép tái sử dụng logic trong các component khác nhau.**

#### Ví dụ:

HOC để thêm state vào component:

```jsx
import React, { useState } from 'react';

// HOC: thêm logic state
function withCounter(WrappedComponent) {
  return function EnhancedComponent(props) {
    const [count, setCount] = useState(0);

    const increment = () => setCount(count + 1);

    return ;
  };
}

// Component được nâng cấp
function Button({ count, increment }) {
  return Clicked {count} times;
}

// Cách dùng HOC
const EnhancedButton = withCounter(Button);

export default EnhancedButton;
```

#### Các trường hợp dùng HOC thực tế:

1. **Xác thực:** Bọc component để kiểm tra quyền truy cập.

2. **Xử lý dữ liệu:** Kết nối với API hoặc xử lý state.

3. **Logging:** Thêm logging cho các hành động component.

#### Hạn chế của HOC:

- Có thể tạo nesting sâu trong cây component nếu dùng quá nhiều HOC.

- Có thể giảm khả năng đọc vì wrapper component thêm vào.

HOC là công cụ mạnh để tái sử dụng logic, nhưng trong ứng dụng hiện đại thường được thay thế bởi React Hooks.

</details>

<details>
<summary>32. Prop `children` là gì?</summary>

#### React

#### Prop `children` là gì?

`children` là prop đặc biệt trong React được dùng để truyền các phần tử hoặc component lồng nhau vào component wrapper.

#### Cách hoạt động?

Khi bạn truyền nội dung con giữa thẻ mở và đóng của component, nội dung đó tự động được truyền dưới dạng `props.children`.

#### Ví dụ:

- **Component wrapper:**

```jsx
function Wrapper({ children }) {
  return { children };
}
```

- **Cách dùng:**

```jsx
function App() {
  return (

      Hello, World!
      This is a paragraph inside the wrapper.

  );
}
```

- **Kết quả:**

```html
Hello, World! This is a paragraph inside the wrapper.
```

#### Các tính năng chính của `children`:

1. **Linh hoạt:** Bạn có thể truyền bất kỳ loại dữ liệu nào: văn bản, JSX, component hoặc mảng phần tử.

2. **Tái sử dụng:** Component wrapper có thể render động các nội dung khác nhau.

3. **Composition có cấu trúc:** Giúp tạo component với cấu trúc lồng nhau.

#### Dùng `children` với function prop:

Đôi khi `children` được dùng như một hàm để truyền dữ liệu động:

```jsx
function List({ items, children }) {
  return {items.map(item => children(item))};
}

function App() {
  return (
    <List items={['Apple', 'Banana', 'Cherry']}>
      {item => {item}}

  );
}
```

#### Kết quả:

```html
Apple Banana Cherry
```

`children` là công cụ mạnh để tạo component toàn dụng và tái sử dụng trong React.

</details>

<details>
<summary>33. Portal là gì?</summary>

#### React

**Portal** trong React là cách render các phần tử con vào DOM node tồn tại bên ngoài phân cấp DOM của component cha.

#### Cách hoạt động:

React cung cấp portal qua phương thức `ReactDOM.createPortal`, nhận hai đối số:

1. **React element** để render.

2. **DOM node đích** nơi phần tử sẽ được chèn vào.

#### Cú pháp:

```jsx
ReactDOM.createPortal(child, container);
```

- **`child`** là React element để render.

- **`container`** là DOM node nơi phần tử sẽ được chèn.

#### Ví dụ:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function Modal({ children }) {
  return ReactDOM.createPortal(
    {children},
    document.getElementById('modal-root') // Node đích
  );
}

function App() {
  return (

      Main content

        This is modal content



  );
}
```

#### Nơi portal được dùng:

- Modal.

- Tooltip.

- Context menu.

#### Đặc điểm:

1. **Phân cấp sự kiện:** Mặc dù phần tử được render bên ngoài phân cấp DOM, xử lý sự kiện vẫn theo phân cấp React component. Ví dụ, sự kiện `onClick` sẽ bubble lên component React cha.

2. **Linh hoạt:** Portal cho phép chèn phần tử vào những nơi không phù hợp với cấu trúc DOM hiện tại.

#### Ưu điểm:

- Quản lý dễ các phần tử "nổi".
- Bảo toàn React context kể cả bên ngoài phân cấp DOM chính.

</details>

<details>

<summary>34. Portal hoạt động như thế nào trong React và ưu điểm, trường hợp dùng UI chính là gì?</summary>

#### React

**Portal** trong React cho phép render các phần tử con vào một phần khác của DOM thay vì vị trí render mặc định của component. Điều này hữu ích để đặt các phần tử nên tồn tại bên ngoài phân cấp DOM thông thường, như modal, tooltip hoặc phần tử nổi.

#### Ưu điểm chính của portal:

- Cho phép render phần tử ở nơi khác trong DOM mà không làm hỏng cấu trúc React component.

- Hữu ích khi phần tử cần được render phủ lên nội dung khác (ví dụ modal hoặc menu pop-up).

#### Cách portal hoạt động:

- Portal cho phép gửi nội dung đến bất kỳ nơi nào trong DOM, kể cả bên ngoài React container gốc.

#### Ví dụ portal:

```jsx
import ReactDOM from 'react-dom';

const Modal = () => {
  return ReactDOM.createPortal(
    <div className="modal">
      <h1>This is a modal window</h1>
    </div>,
    document.getElementById('modal-root') // DOM node nơi portal được render
  );
};

const App = () => {
  return (
    <div>
      <h1>Main page</h1>
      <Modal />
    </div>
  );
};
```

#### Các điểm chính:

- `ReactDOM.createPortal()` được dùng để tạo portal. Đối số đầu tiên là nội dung để render, đối số thứ hai là DOM element mà nội dung đó được chèn vào.

- Portal có thể dùng cho modal, tooltip, menu pop-up và các phần tử khác cần hiển thị bên ngoài cây component chính.

#### Đặc điểm:

- Mặc dù các phần tử được render qua portal nằm bên ngoài phân cấp React component chính, chúng vẫn có quyền truy cập context, state và props của component cha.

- Portal hữu ích khi phần tử cần được đặt "phía trên" nội dung khác hoặc ở cấp phân cấp DOM khác (ví dụ modal không bị giới hạn bởi container cha).

Portal cho phép bảo toàn logic và cấu trúc component mà không vi phạm quy tắc DOM, giúp tạo ra UI component sạch và tiện dụng.

</details>

<details>
<summary>35. Các lifecycle method của component trong React là gì?</summary>

#### React

Các lifecycle method của component trong React được dùng để quản lý các giai đoạn khác nhau của vòng đời component: tạo, cập nhật và xóa.

#### Các giai đoạn lifecycle chính:

1. **Mounting:** Khi component được thêm vào DOM.

`constructor()`: Khởi tạo state và bind phương thức.

`static getDerivedStateFromProps(props, state)`: Cập nhật state trước render (ít dùng).

`render()`: Render JSX vào virtual DOM.

`componentDidMount()`: Gọi ngay sau khi component được thêm vào DOM. Dùng cho API request và khởi tạo thư viện.

2. **Updating:** Khi props hoặc state thay đổi.

`static getDerivedStateFromProps(props, state)`: Gọi trước mỗi lần render.

`shouldComponentUpdate(nextProps, nextState)`: Kiểm soát liệu component có nên render lại hay không. Mặc định trả về `true`.

`render()`: Chạy để cập nhật virtual DOM.

`getSnapshotBeforeUpdate(prevProps, prevState)`: Lấy snapshot trước thay đổi (ví dụ: vị trí scroll).

`componentDidUpdate(prevProps, prevState, snapshot)`: Gọi sau khi cập nhật. Dùng cho request lặp lại hoặc làm việc với DOM.

3. **Unmounting:** Khi component bị xóa khỏi DOM.

`componentWillUnmount()`: Dùng để dọn dẹp tài nguyên (ví dụ: timer hoặc subscription).

4. **Xử lý lỗi:** Khi component throw lỗi.

`static getDerivedStateFromError(error)`: Cho phép cập nhật state sau lỗi.

`componentDidCatch(error, info)`: Log lỗi.

</details>

<details>
<summary>36. useEffect hook là gì và cách dùng?</summary>

#### React

`useEffect` là hook React cho phép thực hiện side effect trong functional component. Side effect bao gồm các thao tác như fetch dữ liệu, đăng ký subscription, đặt timer, thay đổi DOM trực tiếp, v.v.

#### Cú pháp:

```jsx
useEffect(() => {
  // Code side effect
  return () => {
    // Cleanup (tùy chọn)
  };
}, [dependencies]);
```

#### Ví dụ cơ bản:

```jsx
import React, { useState, useEffect } from 'react';

function Timer() {
  const [seconds, setSeconds] = useState(0);

  useEffect(() => {
    const interval = setInterval(() => {
      setSeconds(prev => prev + 1);
    }, 1000);

    return () => clearInterval(interval); // Cleanup
  }, []); // Mảng dependency rỗng = chạy một lần khi mount

  return <p>Seconds: {seconds}</p>;
}
```

#### Mảng dependency:

- **`[]`** — Effect chạy một lần khi mount.
- **`[value]`** — Effect chạy lại khi `value` thay đổi.
- **Không có mảng** — Effect chạy sau mỗi lần render.

</details>

<details>
<summary>37. useState hook là gì?</summary>

#### React

`useState` là hook cơ bản trong React cho phép thêm local state vào functional component.

#### Cú pháp:

```jsx
const [state, setState] = useState(initialValue);
```

- `state` — Giá trị trạng thái hiện tại.
- `setState` — Hàm để cập nhật trạng thái.
- `initialValue` — Giá trị ban đầu của trạng thái.

#### Ví dụ:

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increment</button>
      <button onClick={() => setCount(count - 1)}>Decrement</button>
    </div>
  );
}
```

#### Lưu ý:

- Gọi `setState` kích hoạt render lại component.
- `useState` có thể dùng nhiều lần trong một component.
- Để cập nhật dựa trên giá trị trước: `setCount(prev => prev + 1)`.

</details>

<details>
<summary>38. useCallback hook là gì?</summary>

#### React

`useCallback` là hook trả về phiên bản được memoize của hàm callback. Nó chỉ tạo lại hàm khi các dependency thay đổi.

#### Cú pháp:

```jsx
const memoizedCallback = useCallback(() => {
  doSomething(a, b);
}, [a, b]);
```

#### Khi nào dùng:

- Khi truyền callback xuống component con được tối ưu (dùng `React.memo`).
- Khi hàm được dùng làm dependency trong `useEffect`.

#### Ví dụ:

```jsx
import React, { useState, useCallback } from 'react';

function Parent() {
  const [count, setCount] = useState(0);

  const handleClick = useCallback(() => {
    setCount(prev => prev + 1);
  }, []); // Hàm được tạo một lần

  return <Child onClick={handleClick} />;
}

const Child = React.memo(({ onClick }) => {
  return <button onClick={onClick}>Click me</button>;
});
```

</details>

<details>
<summary>39. useMemo hook là gì?</summary>

#### React

`useMemo` là hook trả về giá trị được memoize từ một tính toán tốn kém. Nó chỉ tính toán lại khi dependency thay đổi.

#### Cú pháp:

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

#### Ví dụ:

```jsx
import React, { useState, useMemo } from 'react';

function ExpensiveComponent({ list }) {
  const [filter, setFilter] = useState('');

  const filteredList = useMemo(() => {
    return list.filter(item => item.includes(filter));
  }, [list, filter]); // Chỉ tính lại khi list hoặc filter thay đổi

  return (
    <div>
      <input value={filter} onChange={e => setFilter(e.target.value)} />
      <ul>{filteredList.map(item => <li key={item}>{item}</li>)}</ul>
    </div>
  );
}
```

#### Khác biệt với `useCallback`:

- `useMemo` memoize **giá trị** (kết quả của hàm).
- `useCallback` memoize **hàm** (bản thân hàm đó).

</details>

<details>
<summary>40. useRef hook là gì?</summary>

#### React

`useRef` là hook trả về đối tượng ref có thể thay đổi với thuộc tính `.current`. Không giống state, thay đổi ref **không** kích hoạt render lại.

#### Cú pháp:

```jsx
const refContainer = useRef(initialValue);
```

#### Hai cách dùng chính:

1. **Truy cập DOM element:**

```jsx
function TextInput() {
  const inputRef = useRef(null);

  const focusInput = () => {
    inputRef.current.focus();
  };

  return (
    <>
      <input ref={inputRef} />
      <button onClick={focusInput}>Focus</button>
    </>
  );
}
```

2. **Lưu giá trị có thể thay đổi (không gây render lại):**

```jsx
function Timer() {
  const intervalRef = useRef(null);

  const start = () => {
    intervalRef.current = setInterval(() => console.log('tick'), 1000);
  };

  const stop = () => {
    clearInterval(intervalRef.current);
  };

  return (
    <>
      <button onClick={start}>Start</button>
      <button onClick={stop}>Stop</button>
    </>
  );
}
```

</details>

<details>
<summary>41. useContext hook là gì?</summary>

#### React

`useContext` là hook cho phép functional component đăng ký vào React context mà không cần bọc bằng Consumer component.

#### Cú pháp:

```jsx
const value = useContext(MyContext);
```

#### Ví dụ:

```jsx
import React, { createContext, useContext } from 'react';

// Tạo context
const ThemeContext = createContext('light');

function ThemedButton() {
  const theme = useContext(ThemeContext);
  return <button className={theme}>Themed Button</button>;
}

function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedButton />
    </ThemeContext.Provider>
  );
}
```

#### Khi nào dùng:

- Chia sẻ dữ liệu toàn cục (theme, người dùng đã đăng nhập, ngôn ngữ) giữa nhiều component.
- Tránh "prop drilling" (truyền props qua nhiều cấp component).

</details>

<details>
<summary>42. Context API là gì?</summary>

#### React

**Context API** là cơ chế tích hợp trong React cho phép chia sẻ dữ liệu giữa các component mà không cần truyền props qua từng cấp trong cây component (tránh "prop drilling").

#### Các thành phần chính:

1. **`React.createContext()`** — Tạo context object.
2. **`Context.Provider`** — Cung cấp giá trị cho cây component con.
3. **`useContext()`** — Hook để đọc giá trị context trong functional component.

#### Ví dụ:

```jsx
import React, { createContext, useContext, useState } from 'react';

const UserContext = createContext(null);

function App() {
  const [user, setUser] = useState({ name: 'Alice' });

  return (
    <UserContext.Provider value={user}>
      <Profile />
    </UserContext.Provider>
  );
}

function Profile() {
  const user = useContext(UserContext);
  return <h1>Hello, {user.name}!</h1>;
}
```

#### Khi nào dùng Context vs. Redux:

- **Context API** — Phù hợp cho dữ liệu đơn giản, ít thay đổi (theme, locale, user).
- **Redux/Zustand** — Phù hợp cho state phức tạp, nhiều thao tác, cần middleware.

</details>

<details>
<summary>43. Custom Hook là gì?</summary>

#### React

**Custom Hook** là hàm JavaScript bắt đầu bằng `use` và có thể gọi các hook khác. Chúng cho phép trích xuất và tái sử dụng logic stateful giữa các component.

#### Ví dụ:

```jsx
import { useState, useEffect } from 'react';

// Custom Hook để fetch dữ liệu
function useFetch(url) {
  const [data, setData] = useState(null);
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState(null);

  useEffect(() => {
    fetch(url)
      .then(res => res.json())
      .then(data => {
        setData(data);
        setLoading(false);
      })
      .catch(err => {
        setError(err.message);
        setLoading(false);
      });
  }, [url]);

  return { data, loading, error };
}

// Cách dùng
function UserList() {
  const { data, loading, error } = useFetch('/api/users');

  if (loading) return <p>Loading...</p>;
  if (error) return <p>Error: {error}</p>;

  return <ul>{data.map(user => <li key={user.id}>{user.name}</li>)}</ul>;
}
```

#### Quy tắc:

- Tên phải bắt đầu bằng `use`.
- Chỉ gọi hook ở cấp cao nhất (không trong vòng lặp, điều kiện).
- Chỉ gọi hook từ React function component hoặc custom hook khác.

</details>

<details>
<summary>44. Redux là gì?</summary>

#### React

**Redux** là thư viện quản lý state có thể dự đoán được cho ứng dụng JavaScript. Thường dùng với React để quản lý trạng thái ứng dụng toàn cục.

#### Các khái niệm cốt lõi:

1. **Store** — Chứa toàn bộ trạng thái ứng dụng.
2. **Action** — Object mô tả điều gì đã xảy ra (`{ type: 'INCREMENT' }`).
3. **Reducer** — Hàm thuần túy nhận state + action, trả về state mới.
4. **Dispatch** — Gửi action đến store.
5. **Selector** — Hàm đọc state từ store.

#### Luồng dữ liệu:

```
UI → dispatch(action) → reducer(state, action) → new state → UI update
```

#### Ví dụ cơ bản:

```jsx
import { createStore } from 'redux';

// Reducer
function counterReducer(state = { count: 0 }, action) {
  switch (action.type) {
    case 'INCREMENT':
      return { count: state.count + 1 };
    case 'DECREMENT':
      return { count: state.count - 1 };
    default:
      return state;
  }
}

// Store
const store = createStore(counterReducer);

store.dispatch({ type: 'INCREMENT' });
console.log(store.getState()); // { count: 1 }
```

#### Khi nào dùng Redux:

- Ứng dụng lớn với nhiều component cần cùng truy cập state.
- State phức tạp với nhiều thao tác.
- Cần debuggability tốt (Redux DevTools).

</details>

<details>
<summary>45. React.memo là gì?</summary>

#### React

`React.memo` là Higher-Order Component (HOC) memoize functional component, ngăn render lại nếu props không thay đổi.

#### Cú pháp:

```jsx
const MemoizedComponent = React.memo(MyComponent);
```

#### Ví dụ:

```jsx
import React from 'react';

const ExpensiveChild = React.memo(({ name, count }) => {
  console.log('Child rendered');
  return <div>{name}: {count}</div>;
});

function Parent() {
  const [count, setCount] = React.useState(0);
  const [other, setOther] = React.useState(0);

  return (
    <div>
      <ExpensiveChild name="Test" count={count} />
      <button onClick={() => setCount(c => c + 1)}>Change count</button>
      <button onClick={() => setOther(o => o + 1)}>Change other</button>
      {/* Click "Change other" sẽ không render lại ExpensiveChild */}
    </div>
  );
}
```

#### So sánh custom:

```jsx
const MemoizedComponent = React.memo(MyComponent, (prevProps, nextProps) => {
  return prevProps.id === nextProps.id; // true = không render lại
});
```

</details>

<details>
<summary>46. Lazy loading trong React là gì?</summary>

#### React

**Lazy loading** là kỹ thuật tải component chỉ khi cần thiết, thay vì tải tất cả khi ứng dụng khởi động. Điều này giảm kích thước bundle ban đầu và cải thiện thời gian tải trang.

#### Sử dụng `React.lazy` và `Suspense`:

```jsx
import React, { Suspense } from 'react';

// Component được tải lazily
const LazyComponent = React.lazy(() => import('./LazyComponent'));

function App() {
  return (
    <div>
      <Suspense fallback={<div>Loading...</div>}>
        <LazyComponent />
      </Suspense>
    </div>
  );
}
```

#### Lưu ý:

- `React.lazy` chỉ hỗ trợ default export.
- `Suspense` là bắt buộc để hiển thị fallback trong khi component đang tải.
- Thường kết hợp với React Router để lazy load theo route.

</details>

<details>
<summary>47. Error Boundary là gì?</summary>

#### React

**Error Boundary** là React component bắt lỗi JavaScript trong cây component con, log chúng và hiển thị fallback UI thay vì làm crash toàn bộ ứng dụng.

#### Cách tạo:

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false };
  }

  static getDerivedStateFromError(error) {
    return { hasError: true };
  }

  componentDidCatch(error, errorInfo) {
    console.error('Error caught:', error, errorInfo);
  }

  render() {
    if (this.state.hasError) {
      return <h1>Something went wrong.</h1>;
    }
    return this.props.children;
  }
}

// Cách dùng
function App() {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
}
```

#### Giới hạn:

Error Boundary **không** bắt lỗi trong:
- Event handler (dùng `try/catch`).
- Async code (setTimeout, Promise).
- Server-side rendering.
- Bản thân Error Boundary.

</details>

<details>
<summary>48. Strict Mode trong React là gì?</summary>

#### React

**Strict Mode** là công cụ phát triển giúp phát hiện các vấn đề tiềm ẩn trong ứng dụng React. Không ảnh hưởng đến production build.

#### Cách bật:

```jsx
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
```

#### Những gì Strict Mode làm:

- Gọi render hai lần (chỉ trong development) để phát hiện side effect không mong muốn.
- Cảnh báo về deprecated lifecycle method.
- Cảnh báo về legacy string ref API.
- Phát hiện unexpected side effect.

</details>

<details>
<summary>49. Controlled Component là gì?</summary>

#### React

**Controlled Component** là form element (input, textarea, select) có giá trị được kiểm soát bởi React state. Nguồn sự thật duy nhất là React state.

#### Ví dụ:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [name, setName] = useState('');
  const [email, setEmail] = useState('');

  const handleSubmit = e => {
    e.preventDefault();
    console.log({ name, email });
  };

  return (
    <form onSubmit={handleSubmit}>
      <input
        type="text"
        value={name}
        onChange={e => setName(e.target.value)}
        placeholder="Name"
      />
      <input
        type="email"
        value={email}
        onChange={e => setEmail(e.target.value)}
        placeholder="Email"
      />
      <button type="submit">Submit</button>
    </form>
  );
}
```

#### Ưu điểm:

- Dễ validate đầu vào.
- Dễ đồng bộ hóa dữ liệu form.
- Có thể kiểm soát khi nào cho phép submit.

</details>

<details>
<summary>50. Uncontrolled Component là gì?</summary>

#### React

**Uncontrolled Component** là form element quản lý state nội bộ của chính nó. Bạn dùng `ref` để truy cập giá trị khi cần, thay vì theo dõi từng thay đổi.

#### Ví dụ:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const nameRef = useRef();
  const emailRef = useRef();

  const handleSubmit = e => {
    e.preventDefault();
    console.log({
      name: nameRef.current.value,
      email: emailRef.current.value,
    });
  };

  return (
    <form onSubmit={handleSubmit}>
      <input type="text" ref={nameRef} placeholder="Name" />
      <input type="email" ref={emailRef} placeholder="Email" />
      <button type="submit">Submit</button>
    </form>
  );
}
```

#### So sánh Controlled vs. Uncontrolled:

| | Controlled | Uncontrolled |
|---|---|---|
| **Nguồn sự thật** | React state | DOM |
| **Truy cập giá trị** | Qua state | Qua ref |
| **Validation** | Dễ | Khó hơn |
| **Cách dùng** | Form phức tạp | Form đơn giản |

</details>

<details>
<summary>51. React Router là gì?</summary>

#### React

**React Router** là thư viện routing tiêu chuẩn cho React, cho phép xây dựng Single Page Application (SPA) với điều hướng phía client mà không reload trang.

#### Cài đặt:

```bash
npm install react-router-dom
```

#### Ví dụ cơ bản (v6):

```jsx
import { BrowserRouter, Routes, Route, Link } from 'react-router-dom';

function App() {
  return (
    <BrowserRouter>
      <nav>
        <Link to="/">Home</Link>
        <Link to="/about">About</Link>
      </nav>

      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/about" element={<About />} />
        <Route path="/users/:id" element={<UserDetail />} />
        <Route path="*" element={<NotFound />} />
      </Routes>
    </BrowserRouter>
  );
}
```

#### Các hook phổ biến:

- `useNavigate()` — Điều hướng programmatically.
- `useParams()` — Truy cập URL parameters.
- `useLocation()` — Truy cập location object.
- `useSearchParams()` — Đọc/ghi query string.

</details>

<details>
<summary>52. Sự khác biệt giữa React Router và routing thông thường là gì?</summary>

#### React

#### Sự khác biệt giữa React Router và routing thông thường:

| Tiêu chí             | React Router                                     | Routing thông thường (Server-Side Routing)       |
| -------------------- | ------------------------------------------------ | ------------------------------------------------ |
| **Loại routing**     | Phía client (SPA)                                | Phía server (MPA)                                |
| **Chuyển trang**     | Không reload trang (JS cập nhật URL)             | Reload trang mỗi lần điều hướng                  |
| **Tốc độ**           | Nhanh hơn vì không yêu cầu server               | Chậm hơn do HTTP request mới                     |
| **SEO**              | Kém hơn nếu không có SSR (Next.js giải quyết)   | Tốt hơn vì nội dung được tải từ server           |
| **Xử lý dữ liệu**    | Render component động                            | Tải HTML từ server                               |
| **Cài đặt**          | Cần React Router                                | Dùng khả năng server tiêu chuẩn                  |

</details>

<details>
<summary>53. Các cách style React component là gì?</summary>

#### React

#### Các cách dùng style trong React component:

1. **Inline style:** Style được truyền trực tiếp dưới dạng object qua thuộc tính `style`.

```jsx
function InlineStyle() {
  const style = { color: 'blue', fontSize: '20px' };
  return <h1 style={style}>Hello, React!</h1>;
}
```

2. **CSS file:** Dùng file CSS thông thường import vào component.

```jsx
import './styles.css';
function CSSFile() {
  return <h1 className="heading">Hello, React!</h1>;
}
```

3. **CSS Modules:** Tạo style cục bộ cho mỗi component.

```jsx
import styles from './styles.module.css';
function CSSModule() {
  return <h1 className={styles.heading}>Hello, React!</h1>;
}
```

4. **Styled Components:** Dùng thư viện `styled-components`.

```jsx
import styled from 'styled-components';
const Heading = styled.h1`color: blue; font-size: 20px;`;
```

5. **Tailwind CSS:** Framework utility class.

```jsx
function TailwindExample() {
  return <h1 className="text-blue-500 text-2xl">Hello, React!</h1>;
}
```

6. **Sass/SCSS:** CSS mở rộng với biến, mixin và nesting.

```jsx
import './styles.scss';
```

</details>

<details>
<summary>54. Ưu điểm của CSS Modules là gì?</summary>

#### React

**Ưu điểm của CSS Modules:**

1. **Phạm vi cục bộ:** Style chỉ áp dụng cho component, không toàn cục. Ngăn xung đột class và đảm bảo style không ảnh hưởng đến các phần khác của ứng dụng.

2. **Tên class duy nhất:** CSS Modules tự động tạo tên class duy nhất, loại bỏ rủi ro xung đột style với component khác.

3. **Bảo trì dễ hơn:** Ít vấn đề hơn khi mở rộng dự án vì mỗi component có style riêng.

4. **Isolation:** Mỗi component có style isolation hoàn toàn, đơn giản hóa refactoring và thay đổi style mà không ảnh hưởng component khác.

5. **Tích hợp dễ với JavaScript:** Bạn có thể dùng style động qua JavaScript bằng cách thay đổi class tùy thuộc vào trạng thái component.

</details>

<details>
<summary>55. Các cách tiếp cận tối ưu hiệu suất ứng dụng React là gì?</summary>

#### React

#### Các cách tối ưu hiệu suất React:

1. **Memoize component:** `React.memo` cho functional component, `PureComponent` cho class component.

2. **Memoize giá trị và hàm:** `useMemo` cho tính toán, `useCallback` cho hàm truyền xuống component con.

3. **Tối ưu render danh sách:** Luôn dùng key duy nhất. Tránh render không cần thiết.

4. **Lazy loading component:** `React.lazy` + `Suspense` để tải component theo yêu cầu.

5. **Kiểm soát re-render:** `shouldComponentUpdate` hoặc `React.memo` để giảm render không cần thiết.

6. **Code splitting:** `React.lazy` và dynamic import để load code chỉ khi cần.

7. **Quản lý state:** Tránh lưu state toàn cục cho component không cần. Dùng Redux, Zustand cho state nặng.

8. **Virtualization danh sách:** `react-window` hoặc `react-virtualized` để chỉ render mục hiển thị.

9. **Tối ưu hình ảnh:** Dùng lazy loading cho ảnh. Nén và tối ưu ảnh.

10. **Build production:** Đảm bảo build ở production mode (`npm run build`).

</details>

<details>
<summary>56. Sự khác biệt giữa `memo` và `useMemo` là gì?</summary>

#### React

#### Sự khác biệt giữa `memo` và `useMemo`

| Tiêu chí                | memo                                                         | useMemo                                                |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------ |
| **Là gì?**              | Higher-order function (HOC)                                  | Hook                                                   |
| **Mục đích**            | Ngăn render lại component nếu props không thay đổi           | Cache kết quả tính toán giữa các lần render            |
| **Dùng ở đâu?**         | Bọc component                                                | Bên trong component                                    |
| **Ví dụ**               | `export default memo(MyComponent);`                          | `const value = useMemo(() => compute(), [deps]);`      |
| **Cache gì?**           | Toàn bộ component                                            | Kết quả hàm                                            |
| **Khi nào dùng?**       | Component nhận cùng props không cần render lại               | Tính toán tốn kém phụ thuộc vào biến                   |

#### Khi nào dùng?

- `memo` khi component nhận cùng props và không cần render lại.

- `useMemo` khi cần lưu kết quả tính toán để không tính lại mỗi lần.

</details>

<details>
<summary>57. Tại sao cần truyền hàm cho `setState()`?</summary>

#### React

Truyền hàm cho `setState()` cần thiết khi trạng thái mới phụ thuộc vào trạng thái trước đó. Điều này đảm bảo cập nhật đúng vì `setState()` hoạt động bất đồng bộ và có thể gộp các lần gọi.

#### Ví dụ có vấn đề:

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  function increment() {
    setCount(count + 1);
    setCount(count + 1);
  }

  return <button onClick={increment}>{count}</button>;
}
```

Ở đây, `count + 1` được tính hai lần từ cùng `count` cũ, nên nút chỉ tăng giá trị lên 1 thay vì 2.

#### Cách đúng:

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  function increment() {
    setCount(prevCount => prevCount + 1);
    setCount(prevCount => prevCount + 1);
  }

  return <button onClick={increment}>{count}</button>;
}
```

Ở đây, `setCount()` nhận giá trị `prevCount` hiện tại, nên increment hoạt động đúng và tăng giá trị lên 2.

</details>

<details>
<summary>58. Làm thế nào để áp dụng validation props trong React?</summary>

#### React

**PropTypes** được dùng để validation props trong React.

1. **Cài đặt PropTypes (nếu chưa cài)**

```sh
npm install prop-types
```

2. **Dùng PropTypes trong functional component:**

```jsx
import React from 'react';
import PropTypes from 'prop-types';

function UserCard({ name, age, isAdmin }) {
  return (
    <div>
      <h2>{name}</h2>
      <p>Age: {age}</p>
      {isAdmin && <p>Admin Access</p>}
    </div>
  );
}

// Định nghĩa PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Giá trị mặc định
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

#### Các PropTypes khả dụng:

- `PropTypes.string`
- `PropTypes.number`
- `PropTypes.bool`
- `PropTypes.array`
- `PropTypes.object`
- `PropTypes.func`
- `PropTypes.node` (JSX hoặc text)
- `PropTypes.element` (React element)
- `PropTypes.oneOf(['value1', 'value2'])` (danh sách giá trị cho phép)
- `PropTypes.shape({ key: PropTypes.type })` (object với cấu trúc định nghĩa)

#### Tóm tắt:

PropTypes giúp tránh lỗi bằng cách kiểm tra kiểu prop, nhưng trong TypeScript điều này được thực hiện ở cấp ngôn ngữ.

</details>

<details>
<summary>59. Các phương pháp tối ưu hiệu suất React là gì?</summary>

#### React

#### Kỹ thuật tối ưu hiệu suất React:

1. **Memoize component:** `React.memo()`, `useMemo()`, `useCallback()`.

2. **Tối ưu re-render:** Tránh state và props không cần thiết. `shouldComponentUpdate` và `React.PureComponent` cho class component.

3. **Virtualization danh sách:** `react-window` hoặc `react-virtualized`.

4. **Caching và debouncing:** `useMemo()` và `useCallback()` cho tính toán nặng. `lodash.debounce` hoặc `lodash.throttle` cho đầu vào người dùng.

5. **Lazy loading:** `React.lazy()` + `Suspense`. Dynamic import.

6. **Tránh side effect không cần thiết trong `useEffect`:** Truyền dependency đúng. Dùng `useRef` để lưu giá trị không render lại.

7. **Tối ưu hình ảnh:** `next/image` trong Next.js. Tối ưu kích thước và format.

8. **Tách state:** Dùng local state khi không cần global. Redux, Zustand hoặc Recoil cho thay đổi toàn cục.

9. **Web Workers:** Cho tính toán nặng để không block main thread.

</details>

<details>
<summary>60. Có thể dùng `async/await` trong React không?</summary>

#### React

Có, `async/await` có thể dùng trong React, nhưng có một số điểm cần lưu ý:

1. **Dùng trong component:** `async/await` không thể dùng trực tiếp trong body component ở vị trí render logic hoặc trong phương thức như `render()`. Tuy nhiên, bạn có thể dùng trong event handler hoặc bên trong hook như `useEffect`.

2. **Công cụ cho async request:**

- Dùng `async/await` bên trong hàm được gọi từ hook:

```jsx
useEffect(() => {
  const fetchData = async () => {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  };
  fetchData();
}, []);
```

3. **Xử lý lỗi:** Đừng quên dùng `try/catch` để xử lý lỗi trong async request:

```jsx
const fetchData = async () => {
  try {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  } catch (error) {
    console.error('Error fetching data:', error);
  }
};
```

Vì vậy, `async/await` có thể và nên dùng cho các thao tác bất đồng bộ trong React, nhưng phải được tổ chức đúng trong component.

</details>

<details>
<summary>61. Lịch sử phát triển của React là gì?</summary>

#### React

#### Lịch sử phát triển ngắn gọn của React:

1. **2011** — React được tạo ra tại Facebook cho nhu cầu nội bộ bởi kỹ sư Jordan Walke để giải quyết vấn đề cập nhật giao diện hiệu quả.

2. **2013** — Facebook phát hành React dưới dạng open-source. Ban đầu cộng đồng hoài nghi vì JSX có vẻ bất thường.

3. **2015** — React 0.14 được phát hành: React và ReactDOM được tách ra, làm thư viện modular hơn. React Native được giới thiệu.

4. **2016** — React 15 với cải tiến hiệu suất qua rendering engine mới.

5. **2017** — React 16 (Fiber): kiến trúc mới cải thiện hiệu suất và hỗ trợ async rendering. Thêm portal và Error Boundary.

6. **2018** — Facebook giới thiệu React Hooks, cho phép dùng state và lifecycle trong functional component.

7. **2019** — React 16.8 với hỗ trợ hook chính thức. Concurrent Mode cải tiến experimental.

8. **2020** — React 17: đơn giản hóa nâng cấp React dần dần trong dự án lớn.

9. **2022** — React 18: Concurrent Rendering và các API mới `useTransition`, `useDeferredValue`.

10. **2024** — React 19: SSR cải tiến, `use` function, React Compiler.

#### Thay đổi chính qua thời gian:

- Từ class component sang functional component với hook.
- Hỗ trợ server-side rendering (SSR).
- Concurrent Mode cho cập nhật giao diện mượt mà hơn.
- Tích hợp React với phát triển mobile qua React Native.

</details>

<details>
<summary>62. React 19 có những tính năng mới gì?</summary>

#### React

React 19 giới thiệu nhiều cập nhật quan trọng nhằm cải thiện hiệu suất và trải nghiệm developer:

1. **Hệ thống rendering mới:** Async rendering cho phép React quản lý cập nhật giao diện hiệu quả hơn.

2. **React Compiler:** Compiler mới tự động tối ưu re-render, giảm cập nhật không cần thiết.

3. **Actions API:** Cách tiếp cận mới để quản lý state và data mutation phía server.

4. **Cơ chế Suspense cải tiến:** Kiểm soát tốt hơn việc tải dữ liệu bất đồng bộ.

5. **Hook `use`:** Hook mới đơn giản hóa làm việc với async data và cải thiện hỗ trợ server component.

6. **Hỗ trợ native cho meta tag:** `meta`, `title`, `link` và các thẻ khác được hỗ trợ mà không cần thư viện thêm.

</details>

<details>
<summary>63. React developer khuyến nghị dùng gì sau khi Create React App bị deprecated?</summary>

#### React

Sau khi Create React App kết thúc hỗ trợ vào tháng 2 năm 2025, developer được khuyến nghị dùng các framework hiện đại:

#### Framework được khuyến nghị:

1. **Next.js:** SSR, SSG và tối ưu SEO.

2. **React Router:** Xây dựng SPA với dynamic routing.

3. **Expo:** Phát triển React Native đơn giản hóa cho ứng dụng mobile đa nền tảng.

</details>

<details>
<summary>64. Hook `useDeferredValue` hoạt động như thế nào trong React?</summary>

#### React

`useDeferredValue` là React hook xuất hiện trong React 18 như một phần của tính năng Concurrent. Nó cho phép trì hoãn cập nhật của các giá trị nhất định, giảm độ ưu tiên của chúng và cho React cơ hội cập nhật giao diện với công việc quan trọng hơn trước.

Điều này rất hữu ích khi giá trị thay đổi thường xuyên và cập nhật giao diện ở mỗi lần thay đổi tốn nhiều tài nguyên.

##### `useDeferredValue` dùng để làm gì?

- Tránh delay và lag trong ứng dụng phức tạp quan trọng đến UI responsiveness.
- Cải thiện tương tác người dùng, đặc biệt khi nhiều dữ liệu thay đổi (tìm kiếm, lọc, render danh sách lớn).
- Đảm bảo animation và chuyển đổi giữa các state mượt mà.

##### Cách hoạt động?

```jsx
const deferredValue = useDeferredValue(value);
```

- React ngay lập tức cập nhật các thay đổi quan trọng (ưu tiên cao).
- Giá trị deferred (`deferredValue`) được cập nhật bất đồng bộ sau khi React xử lý xong các tác vụ khẩn hơn.

##### Ví dụ:

###### Không có `useDeferredValue`:

```jsx
import { useState, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(query));
  }, [items, query]);

  return (
    <>
      <input value={query} onChange={e => setQuery(e.target.value)} placeholder="Search..." />
      <List items={filteredItems} />
    </>
  );
}
```

###### Với `useDeferredValue`:

```jsx
import { useState, useDeferredValue, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');
  const deferredQuery = useDeferredValue(query);

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(deferredQuery));
  }, [items, deferredQuery]);

  return (
    <>
      <input value={query} onChange={e => setQuery(e.target.value)} placeholder="Search..." />
      <List items={filteredItems} />
    </>
  );
}
```

Trong phiên bản này, đầu vào người dùng vẫn tức thì và mượt mà trong khi lọc danh sách thực hiện bất đồng bộ.

##### Khi nào dùng `useDeferredValue` tốt nhất?

- Danh sách với nhiều mục.
- Form với lọc tích cực và autocomplete.
- Bất kỳ trường hợp nào cập nhật giao diện thường xuyên có thể tạo trải nghiệm người dùng không tốt.

</details>

<details>
<summary>65. Refs được dùng như thế nào trong React để tương tác với DOM element?</summary>

#### React

Refs trong React được dùng để truy cập trực tiếp DOM element hoặc component, bỏ qua cơ chế props và state tiêu chuẩn.

1. **Tạo ref:** Dùng `React.createRef()` để tạo ref.

```jsx
const myRef = React.createRef();
```

2. **Gắn ref vào element:** Ref được truyền vào DOM element qua thuộc tính `ref`.

```jsx
<input ref={myRef} />
```

3. **Tương tác với DOM:** Ref cung cấp quyền truy cập DOM element qua `.current`. Ví dụ, để set focus:

```jsx
myRef.current.focus();
```

4. **Giới hạn:** Refs không nên dùng để quản lý state. Chúng chỉ dùng cho tương tác DOM khi cần thiết (ví dụ: focus, chọn text, hoặc animation).

5. **Functional component:** Trong React 16.8 trở lên, `useRef` được dùng cho functional component.

```jsx
const inputRef = useRef();
inputRef.current.focus();
```

</details>

<details>
<summary>66. Làm thế nào để dùng InnerHTML trong React?</summary>

#### React

Trong React, thuộc tính `dangerouslySetInnerHTML` được dùng để chèn nội dung HTML vào DOM. Cách này cho phép chèn HTML trực tiếp vào component, nhưng có thể nguy hiểm vì được gọi là "nguy hiểm" — nó cho phép nhúng HTML thô, có thể dẫn đến tấn công XSS nếu dữ liệu không được làm sạch.

#### Ví dụ dùng `dangerouslySetInnerHTML`:

```jsx
const MyComponent = () => {
  const htmlContent = '<p>This is <strong>HTML</strong> content.</p>';

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
};
```

#### Khi nào dùng:

- Nếu bạn chắc chắn dữ liệu an toàn (ví dụ: từ server của chính bạn).
- Khi cần nhúng nội dung HTML động, như bài viết có markup HTML.

**Cảnh báo bảo mật:** Không bao giờ dùng `dangerouslySetInnerHTML` để chèn dữ liệu nhận từ người dùng hoặc nguồn ngoài mà không làm sạch trước. Dùng thư viện như DOMPurify để tránh tấn công XSS.

```jsx
import DOMPurify from 'dompurify';

const MyComponent = () => {
  const dirtyHtml = "<img src=x onerror=alert('XSS')>";
  const cleanHtml = DOMPurify.sanitize(dirtyHtml);

  return <div dangerouslySetInnerHTML={{ __html: cleanHtml }} />;
};
```

</details>

<details>
<summary>67. ReactDOMServer là gì?</summary>

#### React

**`ReactDOMServer`** là thư viện đi kèm với React được dùng để render React component trên server, tức là cho server-side rendering (SSR). Nó cho phép tạo HTML trên server và gửi đến client, giúp cải thiện hiệu suất và SEO.

#### Các phương thức chính:

1. **`ReactDOMServer.renderToString()`:** Render React element thành chuỗi HTML. Đây là phương thức chính để tạo HTML tĩnh cho lần tải trang đầu tiên.

```jsx
import ReactDOMServer from 'react-dom/server';
const html = ReactDOMServer.renderToString(<App />);
```

2. **`ReactDOMServer.renderToStaticMarkup()`:** Render HTML không có các thuộc tính React thêm vào như `data-reactroot`. Phù hợp để tạo trang hoàn toàn tĩnh.

```jsx
const html = ReactDOMServer.renderToStaticMarkup(<App />);
```

3. **`ReactDOMServer.hydrate()`:** Dùng ở phía client để "hydrate" HTML được render từ server, tức là gắn tính tương tác React vào HTML sẵn có.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

`ReactDOMServer` cho phép tạo trang được pre-render, cải thiện tốc độ tải và hữu ích cho SEO.

</details>

<details>
<summary>68. Package `react-dom` được dùng để làm gì?</summary>

#### React

Package `react-dom` được dùng để tương tác giữa React và DOM thực trong ứng dụng web. Các chức năng chính:

1. **`ReactDOM.render()`:** Render component vào DOM thực. Đây là phương thức chính kết nối React với HTML element.

```jsx
ReactDOM.render(<App />, document.getElementById('root'));
```

2. **`ReactDOM.hydrate()`:** Dùng để hydrate HTML được render từ server (ví dụ: SSR).

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

3. **`ReactDOM.createPortal()`:** Cho phép render element con ở nơi khác trong DOM, bên ngoài phân cấp component thông thường.

```jsx
ReactDOM.createPortal(<Modal />, document.getElementById('modal-root'));
```

4. **`ReactDOM.unmountComponentAtNode()`:** Xóa React component khỏi DOM.

```jsx
ReactDOM.unmountComponentAtNode(document.getElementById('root'));
```

5. **`ReactDOM.findDOMNode()`:** Cung cấp quyền truy cập DOM element thực của component (ít dùng vì có cách hiện đại hơn qua refs).

</details>

<details>
<summary>69. Làm thế nào để dùng `React.lazy` và `React.Suspense` cho code splitting?</summary>

#### React

`React.lazy` và `React.Suspense` được dùng để **tải component động** trong React, cho phép **code splitting**. Điều này có nghĩa là các phần code chỉ được tải khi cần, cải thiện hiệu suất ứng dụng.

#### Cách hoạt động:

1. **`React.lazy()`** cho phép tải component lazily.

2. **`React.Suspense`** bọc phần code chưa tải và hiển thị fallback content (ví dụ: loader) trong khi component đang tải.

#### Ví dụ:

```jsx
// Component được tải động
const MyComponent = React.lazy(() => import('./MyComponent'));

function App() {
  return (
    <div>
      <h1>Ứng dụng của tôi</h1>
      <React.Suspense fallback={<div>Đang tải...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

#### Ưu điểm:

- Cải thiện hiệu suất bằng cách tải component chỉ khi cần.
- Giảm kích thước bundle ban đầu vì các phần ứng dụng được tải theo yêu cầu.

</details>

<details>
<summary>70. Các best practice bảo mật trong React là gì?</summary>

#### React

#### Best practice bảo mật trong React:

1. **Ngăn XSS (Cross-Site Scripting):**
   - Luôn làm sạch dữ liệu từ người dùng trước khi hiển thị trong component.
   - Dùng JSX (React escape input tự động, nhưng tránh dùng `dangerouslySetInnerHTML` khi có thể).

2. **Tránh code injection:**
   - Không truyền dữ liệu chưa validated vào `eval()`, `setTimeout()`, `setInterval()`.

3. **Truy cập API an toàn:**
   - Dùng HTTPS để bảo vệ dữ liệu truyền qua mạng.
   - Dùng authentication, authorization và cookie bảo mật (`HttpOnly`, `Secure`).

4. **Bảo vệ chống CSRF:**
   - Dùng CSRF token để validate tất cả request thay đổi dữ liệu trên server.
   - Dùng flag `SameSite` cho cookie để giới hạn truy cập cùng domain.

5. **Kiểm soát truy cập:**
   - Kiểm tra quyền người dùng trước khi gửi request đến server.
   - Không tin tưởng kiểm tra phía client. Tất cả kiểm tra server-side phải là cuối cùng.

6. **Cập nhật dependency:**
   - Thường xuyên kiểm tra và cập nhật dependency. Dùng `npm audit`.

7. **Quản lý bí mật:**
   - Không lưu trữ bí mật (API key, mật khẩu) trong code client-side.

8. **Dùng Content Security Policy (CSP):**
   - Dùng CSP để ngăn script không mong muốn thực thi trên site.

9. **Bảo vệ chống Clickjacking:**
   - Dùng header `X-Frame-Options` hoặc `Content-Security-Policy` để ngăn site bị nhúng trong `<iframe>`.

</details>

<details>
<summary>71. Làm thế nào để xử lý lỗi trong React dùng Error Boundary?</summary>

#### React

**Error Boundary** trong React cho phép bắt lỗi trong component trong quá trình rendering, trong lifecycle method và trong constructor, xử lý chúng mà không làm crash toàn bộ ứng dụng.

#### Cách implement Error Boundary:

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }

  static getDerivedStateFromError(error) {
    return { hasError: true, error };
  }

  componentDidCatch(error, info) {
    console.error('Lỗi bắt được:', error, info);
  }

  render() {
    if (this.state.hasError) {
      return <h1>Đã xảy ra lỗi.</h1>;
    }
    return this.props.children;
  }
}

const App = () => {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
};
```

#### Lưu ý quan trọng:

Error Boundary **không** bắt lỗi trong event handler, code bất đồng bộ, timer hoặc network request. Dùng `try...catch` cho các trường hợp đó.

</details>

<details>
<summary>72. Inheritance Inversion là gì?</summary>

#### React

**Inheritance Inversion** là tình huống trong đó class được cho là class cơ sở thực sự phụ thuộc vào các lớp kế thừa của nó hoặc mất kiểm soát logic trong phân cấp kế thừa.

#### Vấn đề với inheritance inversion:

- Vi phạm Liskov Substitution Principle (LSP).
- Khó thay đổi hoặc mở rộng class cơ sở mà không ảnh hưởng đến tất cả lớp kế thừa.

#### Ví dụ thực hành kém:

```js
class Parent {
  method() {
    throw new Error('Method phải được implement trong child');
  }
}

class Child extends Parent {
  method() {
    return 'Implementation trong child';
  }
}
```

#### Thay thế: Composition thay vì inheritance:

```js
class Behavior {
  method() {
    return 'Implementation không có inversion';
  }
}

class Parent {
  constructor() {
    this.behavior = new Behavior();
  }

  method() {
    return this.behavior.method();
  }
}
```

</details>

<details>
<summary>73. Polling là gì và làm thế nào để implement trong React?</summary>

#### React

**Polling** là việc gửi request đến server định kỳ để lấy dữ liệu cập nhật. Hữu ích khi server không hỗ trợ WebSocket hoặc Server-Sent Events.

#### Implement Polling trong React:

1. **Dùng `setInterval`:**

```jsx
import { useState, useEffect } from 'react';

const PollingComponent = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    const fetchData = async () => {
      const response = await fetch('https://api.example.com/data');
      const result = await response.json();
      setData(result);
    };

    fetchData(); // Chạy ngay khi load

    const interval = setInterval(fetchData, 5000); // Poll mỗi 5 giây

    return () => clearInterval(interval); // Cleanup khi unmount
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Đang tải...'}</div>;
};
```

2. **Dùng `setTimeout` cho interval động:**

```jsx
const PollingComponent = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    let isMounted = true;

    const fetchData = async () => {
      try {
        const response = await fetch('https://api.example.com/data');
        const result = await response.json();
        if (isMounted) setData(result);
      } catch (error) {
        console.error('Lỗi request', error);
      } finally {
        if (isMounted) setTimeout(fetchData, 5000);
      }
    };

    fetchData();

    return () => {
      isMounted = false;
    };
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Đang tải...'}</div>;
};
```

#### Tóm tắt:

- `setInterval` phù hợp cho polling liên tục, nhưng có thể tạo overlap request.
- `setTimeout` kiểm soát tốt hơn và phù hợp hơn cho adaptive polling.
- Với tải nặng, xem xét dùng WebSocket hoặc Server-Sent Events.

</details>

<details>
<summary>74. Làm thế nào để implement two-way data binding trong React?</summary>

#### React

Trong React, two-way data binding được implement qua **controlled component**, trong đó state component được đồng bộ với input field.

#### Ví dụ:

```jsx
import { useState } from 'react';

const TwoWayBinding = () => {
  const [value, setValue] = useState('');

  return (
    <div>
      <input
        type="text"
        value={value}
        onChange={e => setValue(e.target.value)}
      />
      <p>Giá trị đã nhập: {value}</p>
    </div>
  );
};

export default TwoWayBinding;
```

#### Cách hoạt động:

1. **`value`** lưu trạng thái hiện tại của giá trị nhập.
2. **`onChange`** cập nhật state khi `input` thay đổi.
3. **`value` được cập nhật** hiển thị trong UI, tạo two-way binding.

</details>

<details>
<summary>75. Reverse Data Flow trong React là gì?</summary>

#### React

Reverse Data Flow trong React có nghĩa là truyền thay đổi state từ component con lên component cha. Đây là ngược lại với luồng dữ liệu thông thường, trong đó cha truyền props cho con.

#### Thường được implement qua callback function:

```jsx
function Parent() {
  const [value, setValue] = useState('');

  const handleChange = newValue => {
    setValue(newValue);
  };

  return <Child onValueChange={handleChange} />;
}

function Child({ onValueChange }) {
  return <input type="text" onChange={e => onValueChange(e.target.value)} />;
}
```

Component con truyền giá trị lên cha qua hàm `onValueChange`, implementing reverse data flow.

</details>

<details>
<summary>76. State mutation là gì và làm thế nào để ngăn chặn?</summary>

#### React

State mutation là việc trực tiếp sửa đổi object hoặc array lưu trữ state mà không tạo bản sao. Trong React, điều này dẫn đến kết quả không thể đoán trước vì React không biết state đã thay đổi và sẽ không render lại component.

#### Để ngăn state mutation:

1. **Tạo bản sao dữ liệu** trước khi thay đổi:
   - Với array: `setItems([...items, newItem])`
   - Với object: `setUser({ ...user, name: 'John' })`

2. **Dùng phương thức không mutate**, như `map()`, `filter()`, `reduce()` cho array, hoặc `Object.assign()` cho object.

Điều này cho phép React theo dõi chính xác thay đổi và render lại component.

</details>

<details>
<summary>77. React Strict Mode là gì? Ưu điểm của nó là gì?</summary>

#### React

**Strict Mode** là công cụ React đặc biệt để phát hiện vấn đề tiềm ẩn trong code. Không ảnh hưởng đến hành vi production, nhưng giúp cải thiện chất lượng code trong quá trình phát triển.

Được bật bằng cách bọc component trong `<React.StrictMode>`:

```jsx
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
```

#### Ưu điểm của Strict Mode:

| **Tính năng** | **Mô tả** |
|---|---|
| **Phát hiện lifecycle method không an toàn** | Cảnh báo về phương thức deprecated. |
| **Gọi hàm hai lần trong development** | Giúp tìm side effect trong `useEffect` và hook khác. |
| **Cảnh báo về API deprecated** | Chỉ ra context cũ và pattern không an toàn. |
| **Phát hiện hành vi không mong muốn** | Gọi `useEffect` hai lần để xác minh cleanup effect đúng. |

</details>

<details>
<summary>78. Các cách được khuyến nghị để kiểm tra static type là gì?</summary>

#### React

1. **TypeScript:** Cách tiếp cận phổ biến và đầy đủ nhất để typing tĩnh trong JavaScript/React. TypeScript thêm strict type vào code, cho phép kiểm tra type tại compile time.

2. **PropTypes:** Cơ chế tích hợp để kiểm tra kiểu prop trong React component. Dùng cho validation tại runtime.

```jsx
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};
```

3. **Flow:** Cơ chế khác cho typing tĩnh trong JavaScript. Kém phổ biến hơn TypeScript.

4. **ESLint với typing plugin:** Bạn có thể dùng ESLint với plugin kiểm tra type, nhưng không cung cấp độ sâu typing như TypeScript.

Khuyến nghị dùng **TypeScript** vì tích hợp tốt với React và cung cấp full static typing tại compile time.

</details>

<details>
<summary>79. Làm thế nào để implement animation trong React?</summary>

#### React

1. **CSS animation:** Cách đơn giản nhất là dùng CSS animation hoặc transition tiêu chuẩn.

```jsx
<div className="my-element">Hello</div>

<style jsx>{`
  .my-element {
    animation: fadeIn 1s ease-in-out;
  }
  @keyframes fadeIn {
    0% { opacity: 0; }
    100% { opacity: 1; }
  }
`}</style>
```

2. **React Transition Group:** Cho animated transition phức tạp hơn giữa các component.

```jsx
import { CSSTransition } from 'react-transition-group';

<CSSTransition in={isVisible} timeout={300} classNames="fade" unmountOnExit>
  <div>Content</div>
</CSSTransition>
```

3. **Framer Motion:** Thư viện animation mạnh mẽ cho React.

```jsx
import { motion } from 'framer-motion';

<motion.div
  animate={{ opacity: 1 }}
  initial={{ opacity: 0 }}
  transition={{ duration: 1 }}
>
  Hello
</motion.div>;
```

4. **React Spring:** Cho physics-based animation.

```jsx
import { useSpring, animated } from 'react-spring';

const props = useSpring({ opacity: 1, from: { opacity: 0 } });
<animated.div style={props}>Hello</animated.div>;
```

Với hiệu ứng animation phức tạp, khuyến nghị dùng **Framer Motion** hoặc **React Spring**.

</details>

<details>
<summary>80. Các animation package phổ biến nhất trong React là gì?</summary>

#### React

1. **Framer Motion** — Một trong những package animation phổ biến nhất cho React. Dễ dùng, hỗ trợ animation và transition, hỗ trợ drag-and-drop.

2. **React Spring** — Thư viện cho physics-based animation. Dùng cách tiếp cận animation dựa trên tính chất vật lý như spring và friction.

3. **GSAP (GreenSock Animation Platform)** — Thư viện animation mạnh mẽ không chỉ cho React. Nổi tiếng về tốc độ và khả năng tạo animation rất phức tạp.

4. **React Transition Group** — Thư viện cốt lõi cho transition animation trong React. Cho phép tạo animation enter, exit và state-change cho component.

5. **Lottie for React** — Cho phép nhúng dễ dàng animation được tạo trong After Effects ở định dạng JSON.

</details>

<details>
<summary>81. React DevTools: Làm thế nào để dùng cho debugging?</summary>

#### React

1. **Cài đặt React DevTools:** Cài extension `React Developer Tools` cho Chrome hoặc Firefox.

2. **Tab chính và cách dùng:**
   - ⚛ **Components** → xem cấu trúc component, state và props.
   - ⚡ **Profiler** → phân tích hiệu suất và phát hiện render không cần thiết.

3. **Debug props và state:** Mở tab Components, chọn component để xem `props`, `state` và `context`. Bạn có thể chỉnh sửa `state` và `props` trực tiếp trong DevTools.

4. **Phát hiện render không cần thiết:** Trong tab Profiler, click "Record", thực hiện tương tác, rồi click "Stop". Kiểm tra mã màu:
   - **Đỏ** → render tốn kém.
   - **Vàng** → chi phí trung bình.
   - **Xanh** → render nhẹ.

5. **Debug Context API:** Nếu dùng React Context, bạn có thể kiểm tra giá trị trong DevTools.

6. **Kiểm tra hook:** DevTools cho phép xem state của hook (`useState`, `useEffect`, `useReducer`).

</details>

<details>
<summary>82. Các linter phổ biến nhất cho React là gì?</summary>

#### React

1. **ESLint** — Linter phổ biến nhất cho JavaScript, hỗ trợ React qua plugin `eslint-plugin-react`. Kiểm tra code style, phát hiện lỗi.

2. **Prettier** — Công cụ định dạng code tự động, thường dùng cùng ESLint để đảm bảo code style nhất quán.

3. **TSLint** — Linter cho TypeScript, hiện đang dần được thay thế bởi ESLint vì linh hoạt hơn.

</details>

<details>
<summary>83. Next.js là gì?</summary>

#### React

**Next.js** là React framework cung cấp giải pháp sẵn có cho server-side rendering (SSR), static generation (SSG), API routes, routing, tối ưu hiệu suất và SEO.

#### Tính năng chính:

- **Hybrid rendering:** hỗ trợ SSR, SSG và ISR (incremental regeneration).
- **Routing tự động:** file trong `pages/` tự động trở thành route.
- **API routes:** tạo server endpoint trong file `pages/api/*`.
- **Tối ưu hiệu suất:** tự động code splitting và giảm bundle.
- **App Router:** cách tiếp cận mới dựa trên React Server Component và `app/`.
- **Hỗ trợ tích hợp Tailwind, TypeScript, ESLint và các công nghệ khác**.

</details>

<details>
<summary>84. Sự khác biệt chính giữa Next.js và React là gì?</summary>

#### React

| **Tiêu chí** | **React** | **Next.js** |
|---|---|---|
| **Loại** | Thư viện để xây dựng UI | Framework dựa trên React |
| **Rendering** | Chỉ client-side (CSR) | Hỗ trợ CSR, SSR, SSG, ISR |
| **Routing** | Implement thủ công qua React Router | File-based routing (`pages/` hoặc `app/`) |
| **SEO** | Hỗ trợ kém do CSR | Hỗ trợ SEO tốt (SSR, SSG) |
| **API routes** | Không có | Tích hợp sẵn khả năng tạo API endpoint |
| **Caching** | Không có cơ chế tích hợp | ISR cho phép trang cập nhật mà không regenerate toàn bộ |
| **Tối ưu hiệu suất** | Dùng giải pháp bên thứ ba | Tích hợp sẵn (code splitting, tải ảnh tự động) |
| **Server Components** | Phụ thuộc vào cấu hình | Tích hợp hỗ trợ React Server Component (`app/`) |

</details>

<details>
<summary>85. React Helmet Async được dùng để làm gì?</summary>

#### React

**React Helmet Async** là phiên bản được tối ưu của React Helmet dùng để cập nhật động `<head>` (meta tag, title, Open Graph tag, v.v.) trong ứng dụng React.

#### Tại sao cần?

1. **Tối ưu SEO:** Cho phép thay đổi tiêu đề trang, meta description và keyword.
2. **`<head>` động:** Bạn có thể thay đổi tag cho mỗi trang mà không reload.
3. **Hỗ trợ SSR:** Khác với React Helmet thông thường, phiên bản này hoạt động đúng trong ứng dụng SSR mà không có vấn đề bất đồng bộ.

#### Ví dụ:

```jsx
import { Helmet } from 'react-helmet-async';

function MyComponent() {
  return (
    <Helmet>
      <title>Trang chủ</title>
      <meta name="description" content="Đây là mô tả trang chủ" />
    </Helmet>
  );
}
```

#### Tốt hơn `react-helmet` vì:
- Hỗ trợ SSR mà không có lỗi bất đồng bộ.
- Nhẹ hơn và nhanh hơn.
- Không gây vấn đề trong `StrictMode`.

</details>

<details>
<summary>86. Distributed Component là gì?</summary>

#### React

**Distributed Component** là khái niệm trong đó component được chia thành nhiều phần độc lập có thể render hoặc thực thi logic riêng biệt, nhưng làm việc cùng nhau.

#### Ví dụ implement:

1. **Code Splitting:** Component chỉ được tải khi cần, giảm kích thước bundle ban đầu.

```jsx
const LazyComponent = lazy(() => import('./LazyComponent'));

function App() {
  return (
    <Suspense fallback={<div>Đang tải...</div>}>
      <LazyComponent />
    </Suspense>
  );
}
```

2. **Container-Presentational Pattern:** Tách logic (container) khỏi presentation.

```jsx
function DataContainer({ children }) {
  const [data, setData] = useState(null);
  useEffect(() => {
    fetch('/api/data').then(res => res.json()).then(setData);
  }, []);
  return children(data);
}
```

3. **Micro Frontends:** Dùng các component tự trị riêng biệt ở các phần khác nhau của ứng dụng.

</details>

<details>
<summary>87. Switching Component là gì?</summary>

#### React

**Switching Component** trong React là pattern trong đó component render động một trong các component con dựa trên điều kiện nhất định.

#### Ví dụ 1: Switch dựa trên state:

```jsx
const SwitchingComponent = ({ type }) => {
  switch (type) {
    case 'success':
      return <SuccessMessage />;
    case 'error':
      return <ErrorMessage />;
    default:
      return <DefaultMessage />;
  }
};
```

#### Ví dụ 2: Dùng với React Router:

```jsx
import { Route, Routes } from 'react-router-dom';

const App = () => {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/about" element={<About />} />
      <Route path="*" element={<NotFound />} />
    </Routes>
  );
};
```

#### Ví dụ 3: Conditional rendering qua object:

```jsx
const components = {
  success: SuccessMessage,
  error: ErrorMessage,
  default: DefaultMessage,
};

const SwitchingComponent = ({ type }) => {
  const Component = components[type] || components.default;
  return <Component />;
};
```

</details>

<details>
<summary>88. Reselect là gì và hoạt động như thế nào?</summary>

#### React

**Reselect** là thư viện để tạo selector hiệu quả trong Redux. Giúp tối ưu việc lấy dữ liệu state và tránh render component không cần thiết qua memoization.

#### Cách Reselect hoạt động:

1. Nhận input selector lấy dữ liệu từ state.
2. Tính toán giá trị dựa trên dữ liệu lấy được.
3. Cache kết quả để không tính lại khi input value không thay đổi.

#### Ví dụ:

```jsx
import { createSelector } from 'reselect';

const selectUsers = state => state.users;
const selectFilter = state => state.filter;

export const selectFilteredUsers = createSelector(
  [selectUsers, selectFilter],
  (users, filter) => users.filter(user => user.role === filter)
);
```

- Không có Reselect, component sẽ kiểm tra toàn bộ mảng `users` mỗi lần render.
- Với Reselect, selector chỉ chạy khi `users` hoặc `filter` thay đổi.

#### Ưu điểm:

- Giảm số lần gọi `mapStateToProps` không cần thiết.
- Tránh render component không cần thiết.
- Kết hợp dễ dàng với Redux.

</details>

<details>
<summary>89. `render` có thể trả về kiểu dữ liệu gì?</summary>

#### React

Phương thức `render()` trong React có thể trả về:

1. **JSX hoặc React element:**
```jsx
return <div>Hello, World!</div>;
```

2. **Mảng element:**
```jsx
return [<li key="1">Item 1</li>, <li key="2">Item 2</li>];
```

3. **Fragment (`React.Fragment`):**
```jsx
return <><h1>Tiêu đề</h1><p>Mô tả</p></>;
```

4. **`null` (không render gì):**
```jsx
return null;
```

5. **Giá trị boolean (bị bỏ qua):**
```jsx
return false; // Không có gì được hiển thị
```

6. **Giá trị text:**
```jsx
return "Hello, World!";
```

7. **Portal:**
```jsx
return createPortal(<div>Modal</div>, document.getElementById('modal-root'));
```

</details>

<details>
<summary>90. React xử lý hoặc hạn chế dùng props của loại nhất định như thế nào?</summary>

#### React

React hạn chế dùng props của loại nhất định với `PropTypes` hoặc `TypeScript`.

1. **Dùng PropTypes:**

```jsx
import PropTypes from 'prop-types';

const MyComponent = ({ name, age, isActive }) => (
  <div>
    <h1>{name}</h1>
    <p>Tuổi: {age}</p>
    <p>{isActive ? 'Hoạt động' : 'Không hoạt động'}</p>
  </div>
);

MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isActive: PropTypes.bool,
};
```

Nếu truyền sai kiểu, React sẽ hiện warning trong console (chỉ ở development mode).

2. **Dùng TypeScript:**

```tsx
type MyComponentProps = {
  name: string;
  age?: number;
  isActive: boolean;
};

const MyComponent: React.FC<MyComponentProps> = ({ name, age, isActive }) => (
  <div>
    <h1>{name}</h1>
    <p>Tuổi: {age}</p>
    <p>{isActive ? 'Hoạt động' : 'Không hoạt động'}</p>
  </div>
);
```

TypeScript báo lỗi trước khi code chạy nếu truyền props sai.

| **Phương thức** | **Ưu điểm** | **Nhược điểm** |
|---|---|---|
| **PropTypes** | Đơn giản, hoạt động với JavaScript | Chỉ kiểm tra runtime, bảo mật yếu hơn |
| **TypeScript** | Typing chặt, bắt lỗi sớm hơn | Cần biên dịch, cú pháp phức tạp hơn |

</details>

<details>
<summary>91. Sự khác biệt giữa rendering và mounting là gì?</summary>

#### React

| **Quá trình** | **Mô tả** |
|---|---|
| **Mounting** | Component được tạo và thêm vào DOM lần đầu tiên. `constructor`, `render`, `componentDidMount` (trong class) hoặc `useEffect` với mảng dependency rỗng (trong functional component) được gọi. |
| **Rendering** | Gọi `render()` hoặc gọi lại functional component để cập nhật nội dung. Xảy ra khi `state`, `props` hoặc `forceUpdate()` thay đổi. |

#### Ví dụ mounting:

```jsx
useEffect(() => {
  console.log('Component đã mount');
}, []); // Chạy một lần khi mount
```

#### Ví dụ rendering:

```jsx
const [count, setCount] = useState(0);

useEffect(() => {
  console.log('Component đã render');
}); // Chạy mỗi lần render

return <button onClick={() => setCount(count + 1)}>+</button>;
```

</details>

<details>
<summary>92. Reactive data flow trong React là gì?</summary>

#### React

**Reactive Data Flow** trong React có nghĩa là thay đổi trong state hoặc props của component tự động dẫn đến cập nhật UI mà không cần kích hoạt rerender thủ công.

#### Nguyên tắc chính:

1. **Luồng dữ liệu một chiều:** React truyền dữ liệu từ trên xuống (từ component cha xuống con).
2. **Cách tiếp cận khai báo:** Bạn mô tả những gì nên được render, và React tự xử lý cập nhật.
3. **Cập nhật tự động:** Nếu `state` hoặc `props` thay đổi, React chỉ render lại các phần đã thay đổi.

#### Ví dụ cập nhật reactive:

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Bộ đếm: {count}</p>
      <button onClick={() => setCount(count + 1)}>Tăng</button>
    </div>
  );
}
```

#### React có hoàn toàn reactive không?

Không. Khác với framework "reactive" như Svelte hoặc Solid.js, React không cập nhật DOM khi biến thay đổi trực tiếp. Nó dùng Virtual DOM và kích hoạt rerender khi `state` hoặc `props` thay đổi.

</details>

<details>
<summary>93. React có reactive không?</summary>

#### React

React không phải là thư viện thuần reactive như Vue hoặc Svelte. Tuy nhiên, React có một số đặc điểm làm nó giống các framework reactive:

1. **Cập nhật UI tự động:** React cập nhật UI tự động khi state hoặc props của component thay đổi, tương tự cách tiếp cận reactive.

2. **Functional component và hook:** Dùng hook như `useState` và `useEffect` tạo hiệu ứng reactive trong đó thay đổi state hoặc props dẫn đến rerender component.

3. **Partial reactivity:** React chỉ render lại các component có state hoặc props thay đổi. Đây là cách tiếp cận reactive, nhưng khác với các framework khác, React không xử lý dependency hoặc giá trị qua observer tự động.

Vì vậy, React có một số nguyên tắc reactive, nhưng không phải framework fully reactive.

</details>

<details>
<summary>94. Bạn biết những cách nào để implement drag-and-drop trong React?</summary>

#### React

Drag-and-drop trong React có thể implement theo một số cách:

1. **Dùng HTML5 Drag-and-Drop API native:**

```jsx
import { useState } from 'react';

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const onDragStart = (e, index) => {
    e.dataTransfer.setData('text/plain', index);
  };

  const onDrop = (e, targetIndex) => {
    const sourceIndex = e.dataTransfer.getData('text/plain');
    const newItems = [...items];
    const [movedItem] = newItems.splice(sourceIndex, 1);
    newItems.splice(targetIndex, 0, movedItem);
    setItems(newItems);
  };

  return (
    <ul>
      {items.map((item, index) => (
        <li key={index} draggable
          onDragStart={e => onDragStart(e, index)}
          onDragOver={e => e.preventDefault()}
          onDrop={e => onDrop(e, index)}>
          {item}
        </li>
      ))}
    </ul>
  );
}
```

2. **Dùng `react-dnd`** — Linh hoạt, hỗ trợ trường hợp phức tạp.

```bash
npm install react-dnd react-dnd-html5-backend
```

3. **Dùng `dnd-kit`** — API hiện đại, nhẹ hơn `react-dnd`.

```bash
npm install @dnd-kit/core @dnd-kit/sortable
```

#### Tóm tắt:

- Đơn giản → **HTML5 Drag-and-Drop API**.
- Kiểm soát linh hoạt → **react-dnd**.
- Tùy chọn hiện đại, nhẹ → **dnd-kit**.

</details>

<details>
<summary>95. Làm thế nào để render HTML code trong React component?</summary>

#### React

Dùng `dangerouslySetInnerHTML`, nhưng cẩn thận: có thể dẫn đến tấn công XSS nếu chèn dữ liệu chưa được làm sạch.

#### Ví dụ:

```jsx
function MyComponent() {
  const htmlContent = "<p style='color: red;'>Đây là HTML code</p>";

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
}
```

Nếu làm việc với dữ liệu động, hãy làm sạch dữ liệu trước khi chèn vào.

</details>

<details>
<summary>96. Làm thế nào để thêm class có điều kiện trong React?</summary>

#### React

1. **Toán tử ternary:**

```jsx
function MyComponent({ isActive }) {
  return (
    <div className={isActive ? 'active-class' : 'inactive-class'}>Hello</div>
  );
}
```

2. **Template string:**

```jsx
function MyComponent({ isHighlighted }) {
  return (
    <div className={`base-class ${isHighlighted ? 'highlighted-class' : ''}`}>
      Hello
    </div>
  );
}
```

3. **Thư viện `clsx`:**

```bash
npm install clsx
```

```jsx
import clsx from 'clsx';

function MyComponent({ isActive, isDisabled }) {
  return (
    <div className={clsx('base-class', {
      'active-class': isActive,
      'disabled-class': isDisabled,
    })}>
      Hello
    </div>
  );
}
```

4. **Thư viện `classnames`** — Tương tự `clsx` nhưng có nhiều tính năng hơn.

#### Tóm tắt:

- Trường hợp đơn giản → toán tử ternary hoặc template string.
- Điều kiện phức tạp → `clsx` hoặc `classnames`.

</details>

<details>
<summary>97. Làm thế nào để chạy code trước khi xóa component khỏi cây?</summary>

#### React

1. **Class component:** `componentWillUnmount`

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Component sắp bị xóa');
  }

  render() {
    return <div>Component của tôi</div>;
  }
}
```

2. **Functional component:** `useEffect` với cleanup

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Component sắp bị xóa');
    };
  }, []);

  return <div>Component của tôi</div>;
}
```

3. **Xử lý trước khi đóng trang (`beforeunload`):**

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Trang đang đóng');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

</details>

<details>
<summary>98. `useReducer()` là gì?</summary>

#### React

`useReducer()` là React hook dùng để quản lý state trong functional component. Là thay thế cho `useState()` phù hợp cho logic cập nhật state phức tạp, đặc biệt khi thay đổi phụ thuộc vào state trước đó.

#### Cú pháp:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` — Hàm nhận `state` và `action`, trả về state mới.
- `initialState` — Trạng thái ban đầu.
- `dispatch` — Hàm gọi reducer với `action` cụ thể.

#### Ví dụ:

```jsx
import { useReducer } from 'react';

const initialState = { count: 0 };

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return { count: state.count + 1 };
    case 'decrement':
      return { count: state.count - 1 };
    default:
      return state;
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);

  return (
    <div>
      <p>Đếm: {state.count}</p>
      <button onClick={() => dispatch({ type: 'increment' })}>+</button>
      <button onClick={() => dispatch({ type: 'decrement' })}>-</button>
    </div>
  );
}
```

#### Khi nào dùng:

- Khi state có logic hoặc dependency phức tạp.
- Khi cần chuẩn hóa cập nhật state qua `dispatch`.
- Để mở rộng, ví dụ khi dùng trong global state.

</details>

<details>
<summary>99. Làm thế nào để dùng `React.lazy` và `React.Suspense` cho code splitting?</summary>

#### React

`React.lazy` và `React.Suspense` được dùng để **tải component động** trong React, cho phép **code splitting**. Điều này có nghĩa là các phần code chỉ được tải khi cần, cải thiện hiệu suất ứng dụng.

#### Cách hoạt động:

1. `React.lazy()` cho phép tải component lazily.
2. `React.Suspense` bọc phần code chưa tải và cho hiển thị fallback content trong khi component đang tải.

#### Ví dụ:

```jsx
// Component được tải động
const MyComponent = React.lazy(() => import('./MyComponent'));

function App() {
  return (
    <div>
      <h1>Ứng dụng của tôi</h1>
      <React.Suspense fallback={<div>Đang tải...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

#### Ưu điểm:

- Cải thiện hiệu suất bằng cách tải component chỉ khi cần.
- Giảm kích thước bundle ban đầu.

</details>

<details>
<summary>100. Các cách tiếp cận để thực hiện HTTP request trong React là gì?</summary>

#### React

React không có API tích hợp để thực hiện HTTP request, nhưng bạn có thể dùng thư viện bên thứ ba hoặc công cụ JavaScript tiêu chuẩn.

1. **Dùng Fetch API:**

```jsx
useEffect(() => {
  fetch('https://jsonplaceholder.typicode.com/posts')
    .then(response => response.json())
    .then(data => setData(data))
    .catch(error => setError(error.message));
}, []);
```

2. **Dùng Axios:**

```jsx
useEffect(() => {
  axios
    .get('https://jsonplaceholder.typicode.com/posts')
    .then(response => setData(response.data))
    .catch(error => setError(error.message));
}, []);
```

3. **React Query (TanStack Query):**

```jsx
const { data, error, isLoading } = useQuery('posts', async () => {
  const response = await axios.get('https://jsonplaceholder.typicode.com/posts');
  return response.data;
});
```

4. **GraphQL (Apollo Client):**

```jsx
const { loading, error, data } = useQuery(GET_POSTS);
```

5. **Custom Hook:**

```jsx
function useFetch(url) {
  const [data, setData] = useState(null);
  const [loading, setLoading] = useState(true);
  useEffect(() => {
    fetch(url).then(r => r.json()).then(d => { setData(d); setLoading(false); });
  }, [url]);
  return { data, loading };
}
```

#### Lựa chọn tùy thuộc vào nhu cầu:
- **Fetch API:** Request đơn giản.
- **Axios:** Cần thêm linh hoạt (interceptor, timeout).
- **React Query:** Quản lý data cache.
- **GraphQL/Apollo Client:** API GraphQL.
- **Custom Hook:** Tái sử dụng logic request.

</details>

<details>
<summary>101. Sự khác biệt giữa `createElement` và `cloneElement` là gì?</summary>

#### React

| **Phương thức** | **Mô tả** | **Trường hợp dùng chính** |
|---|---|---|
| `React.createElement` | Tạo React element mới. Nhận kiểu element, props và element con làm đối số. | Dùng để tạo React element từ đầu, thường trong quá trình render JSX. |
| `React.cloneElement` | Clone React element có sẵn, cho phép thay đổi props hoặc children của nó. | Dùng để tạo bản sao đã chỉnh sửa của React element đang tồn tại. |

#### Ví dụ:

`React.createElement`:
```jsx
const element = React.createElement('div', { className: 'example' }, 'Hello, React!');
// Kết quả: <div class="example">Hello, React!</div>
```

`React.cloneElement`:
```jsx
const originalElement = <button className="primary">Click</button>;
const clonedElement = React.cloneElement(originalElement, { className: 'secondary' });
// Kết quả: <button class="secondary">Click</button>
```

#### Điểm khác biệt:
- `createElement`: Tạo element hoàn toàn mới.
- `cloneElement`: Làm việc từ element có sẵn, cho phép thay đổi props hoặc nội dung.

</details>

<details>
<summary>102. Hàm `lazy` có hỗ trợ named export không?</summary>

#### React

Không, hàm `React.lazy` không hỗ trợ named export. Nó chỉ hoạt động với default export. Nếu bạn có module với named export và muốn dùng với `React.lazy`, bạn cần tạo wrapper export component cần thiết dưới dạng default.

#### Ví dụ wrapper:

```jsx
// Named export
export const MyComponent = () => {
  return <div>Hello, World!</div>;
};

// Dùng React.lazy
const LazyComponent = React.lazy(() =>
  import('./MyComponent').then(module => ({ default: module.MyComponent }))
);

export default LazyComponent;
```

</details>

<details>
<summary>103. Ưu điểm của React là gì?</summary>

#### React

1. **Hiệu suất cao:** Dùng Virtual DOM giảm thiểu cập nhật DOM thực, làm rendering nhanh hơn.

2. **Cách tiếp cận component:** Ứng dụng được xây dựng từ **component tái sử dụng**, đơn giản hóa phát triển và bảo trì.

3. **Luồng dữ liệu một chiều:** Dữ liệu chảy xuống phân cấp component, giúp dễ theo dõi thay đổi state.

4. **Hỗ trợ Hook:** `useState`, `useEffect`, `useMemo` và các hook khác cho phép quản lý state và effect trong functional component.

5. **SSR và SSG:** Với Next.js, có thể tối ưu SEO và cải thiện hiệu suất ứng dụng.

6. **Linh hoạt và hệ sinh thái:** React có thể dùng cùng Redux, Zustand, MobX, React Query. Hỗ trợ React Native cho ứng dụng mobile.

7. **Khả năng debug nâng cao:** React DevTools cho phép kiểm tra cấu trúc component, state và props theo thời gian thực.

8. **Cộng đồng và hỗ trợ Facebook:** Nhiều thư viện, giải pháp sẵn có và phát triển framework nhanh.

</details>

<details>
<summary>104. Hạn chế của React là gì?</summary>

#### React

1. **Nhiều rerender:** Nếu component không được tối ưu đúng, có thể dẫn đến rerender quá mức ảnh hưởng đến hiệu suất.

2. **Cần quản lý state:** Không có quản lý state đúng, ứng dụng có thể khó bảo trì.

3. **Luồng dữ liệu một chiều:** Dữ liệu chỉ chảy một chiều, có thể khó truyền dữ liệu qua nhiều cấp component.

4. **Reactivity:** React cập nhật DOM qua Virtual DOM, nhưng có thể không hiệu quả cho ứng dụng rất lớn, động cao.

5. **Phụ thuộc JavaScript:** Hỗ trợ kém khi không có JavaScript ở phía client.

6. **Đường cong học tập cho người mới:** Mặc dù khái niệm React khá đơn giản, việc thành thạo hook, context và tối ưu có thể khó.

7. **Công cụ bên thứ ba:** Mặc dù có nhiều công cụ, việc tích hợp chúng có thể phức tạp trong dự án lớn.

</details>

<details>
<summary>105. Phương thức `registerServiceWorker()` được dùng để làm gì trong React?</summary>

#### React

`registerServiceWorker()` được dùng để đăng ký Service Worker trong Create React App (trước khi bị xóa khỏi CRA trong phiên bản 4).

#### Mục đích:

- Cache tài nguyên cho chế độ offline.
- Tăng tốc tải ứng dụng.
- Cập nhật tài nguyên nền.

#### Ví dụ dùng (trước CRA 4):

```javascript
import { register } from './serviceWorker';
register();
```

Sau khi bị xóa khỏi CRA, Service Worker phải được cấu hình thủ công qua `navigator.serviceWorker.register()`.

Trong **React 19**, không có `registerServiceWorker()` tích hợp. Nếu cần Service Worker, đăng ký thủ công.

</details>

<details>
<summary>106. Synthetic event (`SyntheticEvent`) trong React là gì?</summary>

#### React

**SyntheticEvent** trong React là wrapper trên các sự kiện browser native cung cấp tương thích cross-browser và cải thiện hiệu suất.

#### Đặc điểm của SyntheticEvent:

- Hoạt động giống nhau trên tất cả browser.
- Dùng event pooling, giúp tránh giữ đối tượng không cần thiết trong bộ nhớ.
- Tất cả sự kiện được chuẩn hóa và có cùng thuộc tính bất kể browser.

#### Ví dụ:

```jsx
function MyComponent() {
  const handleClick = event => {
    console.log(event.type); // "click"
    console.log(event.nativeEvent); // Sự kiện browser gốc
  };

  return <button onClick={handleClick}>Click</button>;
}
```

#### Các phương thức chính:

- `event.preventDefault()` — Ngăn hành vi mặc định.
- `event.stopPropagation()` — Dừng event bubbling.
- `event.persist()` — Tắt pooling để sự kiện không bị reset.

</details>

<details>
<summary>107. Các kỹ thuật tối ưu hiệu suất trong React là gì?</summary>

#### React

1. **Memoize component:** `React.memo()`, `useMemo()`, `useCallback()`.

2. **Tối ưu rerender:** Tránh state và props không cần thiết. Dùng `shouldComponentUpdate` và `React.PureComponent` trong class component. Tối ưu context bằng cách không truyền giá trị không cần thiết.

3. **Virtualization danh sách:** `react-window` hoặc `react-virtualized`.

4. **Caching và debouncing:** `useMemo()` và `useCallback()` cho tính toán nặng. Debouncing (`lodash.debounce`) hoặc throttling (`lodash.throttle`) cho đầu vào người dùng.

5. **Lazy loading:** `React.lazy()` + `Suspense`. Dynamic import.

6. **Tránh side effect không cần thiết trong `useEffect`:** Truyền dependency đúng. Dùng `useRef` để lưu giá trị mà không render lại.

7. **Tối ưu hình ảnh:** `next/image` trong Next.js. Tối ưu kích thước và format (`WebP`, `AVIF`).

8. **Tách state:** Dùng local state khi không cần global. Dùng `Redux`, `Zustand` hoặc `Recoil` cho thay đổi toàn cục.

9. **Web Workers:** Cho tính toán nặng để không block main thread.

</details>

<details>
<summary>108. Có thể dùng `async/await` trong React không?</summary>

#### React

Có, `async/await` có thể dùng trong React, nhưng có một số điểm cần lưu ý:

1. **Dùng trong component:** `async/await` không thể dùng trực tiếp trong body component ở vị trí rendering logic hoặc trong phương thức `render()`. Tuy nhiên, bạn có thể dùng trong event handler hoặc trong hook như `useEffect`.

2. **Công cụ cho async request:**

```jsx
useEffect(() => {
  const fetchData = async () => {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  };
  fetchData();
}, []);
```

3. **Xử lý lỗi:** Dùng `try/catch` để xử lý lỗi trong async request:

```jsx
const fetchData = async () => {
  try {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  } catch (error) {
    console.error('Lỗi fetch dữ liệu:', error);
  }
};
```

</details>

<details>
<summary>109. Lịch sử phát triển của React là gì?</summary>

#### React

1. **2011** — React được tạo ra tại Facebook bởi kỹ sư Jordan Walke để giải quyết vấn đề cập nhật UI hiệu quả.

2. **2013** — Facebook phát hành React dưới dạng open-source.

3. **2015** — React 0.14: React và ReactDOM được tách ra. React Native được giới thiệu.

4. **2016** — React 15 với cải tiến hiệu suất qua rendering engine mới.

5. **2017** — React 16 (Fiber): kiến trúc mới, hiệu suất tốt hơn, hỗ trợ async rendering. Thêm portal và Error Boundary.

6. **2018** — Facebook giới thiệu React Hooks.

7. **2019** — React 16.8 với hỗ trợ hook chính thức. Concurrent Mode cải tiến experimental.

8. **2020** — React 17: đơn giản hóa nâng cấp React dần dần.

9. **2022** — React 18: Concurrent Rendering và API mới `useTransition`, `useDeferredValue`.

10. **2024** — React 19: SSR cải tiến, `use` function, React Compiler.

#### Thay đổi chính:
- Từ class component sang functional component với hook.
- Hỗ trợ server-side rendering (SSR).
- Concurrent Mode cho cập nhật UI mượt hơn.
- Tích hợp React với mobile qua React Native.

</details>

<details>
<summary>110. React 19 có những tính năng mới gì?</summary>

#### React

React 19 giới thiệu nhiều cập nhật quan trọng:

1. **Hệ thống rendering mới:** Async rendering cho phép React quản lý cập nhật UI hiệu quả hơn.

2. **React Compiler:** Compiler mới tự động tối ưu rerender, giảm cập nhật không cần thiết.

3. **Actions API:** Cách tiếp cận mới để quản lý state và data mutation phía server.

4. **Cơ chế Suspense cải tiến:** Kiểm soát tốt hơn việc tải dữ liệu bất đồng bộ.

5. **Hook `use`:** Hook mới đơn giản hóa làm việc với async data và cải thiện hỗ trợ server component.

6. **Hỗ trợ native cho meta tag:** `meta`, `title`, `link` và các tag khác được hỗ trợ mà không cần thư viện thêm.

</details>

<details>
<summary>111. React developer khuyến nghị dùng gì sau khi Create React App bị deprecated?</summary>

#### React

Sau khi hỗ trợ Create React App kết thúc vào tháng 2 năm 2025, developer được khuyến nghị dùng framework hiện đại:

1. **Next.js:** SSR, SSG và tối ưu SEO.
2. **React Router:** Xây dựng SPA với dynamic routing.
3. **Expo:** Đơn giản hóa phát triển React Native cho ứng dụng mobile đa nền tảng.

</details>

<details>
<summary>112. Hook `useDeferredValue` hoạt động như thế nào trong React?</summary>

#### React

`useDeferredValue` là React hook xuất hiện trong React 18 như một phần của Concurrent features. Cho phép trì hoãn cập nhật của các giá trị nhất định, giảm độ ưu tiên của chúng và cho React cơ hội cập nhật UI với công việc quan trọng hơn trước.

Hữu ích khi giá trị thay đổi thường xuyên và cập nhật UI ở mỗi lần thay đổi tốn nhiều tài nguyên.

#### `useDeferredValue` dùng để làm gì?

- Tránh delay và lag trong ứng dụng phức tạp quan trọng đến UI responsiveness.
- Cải thiện tương tác người dùng (tìm kiếm, lọc, render danh sách lớn).
- Đảm bảo animation và chuyển đổi mượt mà.

#### Cách hoạt động:

```jsx
const deferredValue = useDeferredValue(value);
```

- React ngay lập tức cập nhật thay đổi quan trọng (ưu tiên cao).
- Giá trị deferred được cập nhật bất đồng bộ sau khi React xử lý xong các tác vụ khẩn hơn.

#### Ví dụ:

```jsx
import { useState, useDeferredValue, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');
  const deferredQuery = useDeferredValue(query);

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(deferredQuery));
  }, [items, deferredQuery]);

  return (
    <>
      <input
        value={query}
        onChange={e => setQuery(e.target.value)}
        placeholder="Tìm kiếm..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

Đầu vào người dùng vẫn tức thì trong khi lọc danh sách thực hiện bất đồng bộ.

#### Khi nào dùng tốt nhất:

- Danh sách với nhiều mục.
- Form với lọc tích cực và autocomplete.
- Bất kỳ trường hợp nào cập nhật UI thường xuyên có thể tạo trải nghiệm người dùng không tốt.

</details>

<details>
<summary>113. Làm thế nào để tạo form trong React?</summary>

#### React

Form trong React được tạo dùng element `<form>` và các control tương ứng như `<input>`, `<textarea>` và `<select>`. Tính phản hồi của form được cung cấp bởi controlled hoặc uncontrolled component.

#### Controlled form:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [name, setName] = useState('');
  const [email, setEmail] = useState('');

  const handleSubmit = e => {
    e.preventDefault();
    console.log('Đã submit:', { name, email });
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Tên:
        <input type="text" value={name} onChange={e => setName(e.target.value)} />
      </label>
      <br />
      <label>
        Email:
        <input type="email" value={email} onChange={e => setEmail(e.target.value)} />
      </label>
      <br />
      <button type="submit">Submit</button>
    </form>
  );
}
```

#### Uncontrolled form:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const nameRef = useRef();
  const emailRef = useRef();

  const handleSubmit = e => {
    e.preventDefault();
    console.log('Đã submit:', {
      name: nameRef.current.value,
      email: emailRef.current.value,
    });
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>Tên: <input type="text" ref={nameRef} /></label>
      <br />
      <label>Email: <input type="email" ref={emailRef} /></label>
      <br />
      <button type="submit">Submit</button>
    </form>
  );
}
```

#### Điểm chính:

1. **Controlled form:** Dùng `state`. Phù hợp hơn cho form phức tạp cần validation hoặc đồng bộ hóa.

2. **Uncontrolled form:** Dùng `ref`. Cách tiếp cận đơn giản không có logic quản lý state phức tạp.

</details>
