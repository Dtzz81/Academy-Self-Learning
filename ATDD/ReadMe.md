Following videos from our lectures
Learning ATDD, creating https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

Rules:
- Any live cell with fewer than two live neighbours dies, as if by underpopulation.
- Any live cell with two or three live neighbours lives on to the next generation.
- Any live cell with more than three live neighbours dies, as if by overpopulation.
- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

In other words:
- Any live cell with two or three live neighbours survives.
- Any dead cell with three live neighbours becomes a live cell.
- All other live cells die in the next generation. Similarly, all other dead cells stay dead.

To test if rspec works:

describe "something" do
    it "works" do
        expect(true).to eq true
    end
end

What is simplest? :
- If cell has no neighbours, it dies
