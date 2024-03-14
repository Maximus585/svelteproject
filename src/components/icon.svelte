<script>
    export let name;
    const icons = [
        {
            name: 'check-mark',
            path: '<path d="https://icon-icons.com/ru/%D0%B7%D0%BD%D0%B0%D1%87%D0%BE%D0%BA/%D0%B3%D0%B0%D0%BB%D0%BE%D1%87%D0%BA%D0%B0-%D0%9C%D0%B0%D1%80%D0%BA/69146" fill="currentColor"></path>',
        },
        {
            name: 'delete',
            path:  '<path d="https://icon-icons.com/ru/%D0%B7%D0%BD%D0%B0%D1%87%D0%BE%D0%BA/%D0%BC%D1%83%D1%81%D0%BE%D1%80-%D0%9E%D0%93%D0%A0%D0%9D-%D1%83%D0%B4%D0%B0%D0%BB%D0%B8%D1%82%D1%8C-%D1%83%D0%B4%D0%B0%D0%BB%D0%B8%D1%82%D1%8C/67981" fill="currentColor"></path>'
        },
    ];
    let icon = icons.find((item)=>item.name === name);
</script>

