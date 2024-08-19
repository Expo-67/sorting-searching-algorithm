// **\***Implementation of Insertion Sort using JavaScript:**\***//

//**\*\***Javascript imp **\*\***//

const arr =[2,4,9,14,23,7];// goes through each element in the array from left value
const insertionSort = arr =>{
for (let i = 1; i < arr.length; i++) {
let curr =arr[i];
let j = i-1;// i picks out the elements in the arr element -1

        while(j>=0 && arr[j] > curr){// this condition is checking example is 2>4 is 4>9 is 9>14 ....
        arr[j+1] = arr[j];
        j --
        }
        arr[j+1] = curr;

}
return arr;
};
insertionSort(arr);
console.log(arr); //
